Group members: Prit Patel, Jaimeen Sharma
I downloaded the dataset and uploaded it onto the gogle drive. Then, I unzip and install it there. Then I made some edits in given file named 228_training_aerial_imagery.py file and then ran it on google colab.
![1](https://user-images.githubusercontent.com/116983462/200226118-13425bad-beec-452a-8575-37e9c90ce82f.jpg)
![2](https://user-images.githubusercontent.com/116983462/200226127-649e88ca-8bea-46b7-9a05-f3ef3d4fa8bf.jpg)
Next, divide each image by the patch size, which is 256, and read each one as BGR (blue, green, and red). After that, each image's patches were extracted using the patchifying library. then carried out the exact identical action using masks. then the designated building color code After being turned into an RBG array, the labels were applied to the land, roads, vegetation, water, and unlabels. The image was then double-checked to see if it was what was anticipated. Then, since the size of our patch was 256, we imported the multi unetmodel and Jacard coef from another file called simple multi unet model. This image model was created using height and width channels, and it was then assembled in the optimizer "Adam." The model was then put into History 1, and Model fir was performed with a batch size of 16 and epochs of 56. 

![5](https://user-images.githubusercontent.com/116983462/200226157-77ec5a81-78fa-4fc9-9cc4-5538b1b3a798.jpg)
I received the accuracy of 53.48 percent. 

Then I tested for training and validation loss
![3](https://user-images.githubusercontent.com/116983462/200228083-4fb120cb-aebd-4732-be8c-cf0e63cf4430.jpg)
![4](https://user-images.githubusercontent.com/116983462/200228104-dbf832c8-fa46-4db4-9dd1-06e8503254e6.jpg)

And lastly, I got the following results.
![6](![3](https://user-images.githubusercontent.com/116983462/200228054-f3246288-6e41-4cbb-8dd7-b5563cea322a.jpg)
![7](https://user-images.githubusercontent.com/116983462/200226175-5b576bc0-30a2-4057-9a79-064512ec667d.jpg)
![8](https://user-images.githubusercontent.com/116983462/200226202-98f9f6c7-6a63-4bf0-8b67-0b57b62d908b.jpg)
![9](https://user-images.githubusercontent.com/116983462/200226205-2574dbff-83ef-457d-a8d4-9a2b461d106e.jpg)
![10](https://user-images.githubusercontent.com/116983462/200226212-f403f37d-43a7-48c9-8a5b-00b789cd1e9c.jpg)
