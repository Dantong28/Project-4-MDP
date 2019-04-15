Dantong Zhu CS 7641 Project 4

To run the code:
1. Download Eclipse IDE: https://www.eclipse.org/
2. Download or clone my github file repository: https://github.com/Dantong28/Project-4-MDP
3. Import the project into Eclipse
4. Update the project using Maven (right click the project inside Eclipse) - Maven will download Burlap and a bunch of other things that come with it. 
5. Download the latest Java SE Development kit
6. Run the main.java class in the project folder using Eclipse


Experiments with different problems and algorithms:
-There are two problems that are the two MDPs explored and three RL algorithms (value iteration, policy iteration, and Q Learning) in this assignment.
-On line 50: setting PROBLEM to 1 runs the algorithm with the first MDP which is a maze on a 5*5 grid, and setting PROBLEM to 2 runs it with the second MDP which is a maze on a 16*16 grid.
-On line 56, you choose which one of the three RL algorithm to run.


Acknowledgements
1. The source code for this assignment was modified from the original versions found at: http://burlap.cs.brown.edu/
2. https://github.com/kylewest520/CS-7641---Machine-Learning/tree/master/Assignment%204%20Markov%20Decision%20Processes
3. https://github.com/svpino/cs7641-assignment4. I am indebted to this github repository. Please visit it to see the original implementation with extensive notes in the README.