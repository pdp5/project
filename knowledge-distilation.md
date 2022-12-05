Milestone : 4
Group Members Name: Prit Patel, Jaimeen Sharma

During the milsestone 4 of the project, we have worked on how to compress our model to fit a computer that not have GPU. Also, we have used ML for the project.

A very simple way to improve the performance of almost any machine learning algorithm is to train many different models on the same data and then to average their predictions. Unfortunately, making predictions using a whole ensemble of models is cumbersome and may be too computationally expensive to allow deployment to a large number of users, especially if the individual models are large neural nets. Caruana and his collaborators have shown that it is possible to compress the knowledge in an ensemble into a single model which is much easier to deploy and we develop this approach further using a different compression technique. We achieve some surprising results on MNIST and we show that we can significantly improve the acoustic model of a heavily used commercial system by distilling the knowledge in an ensemble of models into a single model. We also introduce a new type of ensemble composed of one or more full models and many specialist models which learn to distinguish fine-grained classes that the full models confuse. Unlike a mixture of experts, these specialist models can be trained rapidly and in parallel.

KnowledgeDistill: 
Knowledge Distillation (KD) is proposed in Distilling the Knowledge in a Neural Network, the compressed model is trained to mimic a pre-trained, larger model. This training setting is also referred to as “teacher-student”, where the large model is the teacher and the small model is the student. KD is often used to fine-tune the pruned model.

![1](https://user-images.githubusercontent.com/116983462/205540912-4e97c9a7-e1fc-4eaf-95bd-f761a0c6ad63.jpg)
![2](https://user-images.githubusercontent.com/116983462/205540915-364b6ece-dd60-4515-b6d5-0eb3e737c9c0.jpg)
![3](https://user-images.githubusercontent.com/116983462/205548218-06a3573d-c011-46f2-984a-6343c80476e7.jpg)
