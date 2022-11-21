Milestone 3:
Group Members: Prit Patel, Jaimeen Sharma

Group2: Anneal Method

This simple annealing algorithm begins by sampling from the prior, but tends over time to sample from points closer and closer to the best ones observed.
This algorithm is a simple variation on the random search that leverages smoothness in the response surface. The annealing rate is not adaptive.

Simulated Annealing can be used to find close to optimal solution in a discrete search space with large number of possible solutions (combination of hyperparameters). It is useful for combinatorial optimization problems defined by complex objective functions (model evaluation metrics).

Simulated Annealing is a probabilistic technique for approximating global optimum of a given function.

The name of this approach is inspired from metallurgy technique of heating and controlled cooling of materials called annealing.

This notion of controlled cooling implemented in the simulated annealing algorithm is interpreted as a slow decrease in the probability of accepting worse solutions as the solution space is explored.

At each step, the simulated annealing heuristic considers some neighboring state s* of the current state s, and probabilistically decides between moving the system to state s* or staying in-state s. These probabilities ultimately lead the system to move to states of lower energy.


![1](https://user-images.githubusercontent.com/116983462/202966881-eaa7c9a7-6338-43ab-8009-c794b314430f.jpg)
![2](https://user-images.githubusercontent.com/116983462/202966889-2401e837-e537-4281-826a-108715d35ae8.jpg)
![3](https://user-images.githubusercontent.com/116983462/202966893-00ca4a8d-ce17-4615-b4b0-117b46902d89.jpg)
