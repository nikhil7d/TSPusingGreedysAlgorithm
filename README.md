# TSPusingGreedysAlgorithm
C++ project to find optimal solution of Travelling Salesman Problem using Greedy's algorithm. The program would take input of no of cities and distances between them and give the shortest possible route to visit all cities and return to origin city. 

The travelling salesman problem is a classic mathematical problem. It is used for optimization in the field of computer science and operational research. 
The problem statement is: given a list of cities and the distance between every pair, find the shortest path that visit each and every city and return to the origin. The problem is best represented by using graphs, where every node is city and the edge between them is the distance between the cities. 


A greedy algorithm, as the name suggests, always makes the choice that seems to be the best at that moment. This means that it makes a locally-optimal choice in the hope that this choice will lead to a globally-optimal solution.
How do you decide which choice is optimal?
Assume that you have an objective function that needs to be optimized (either maximized or minimized) at a given point. A Greedy algorithm makes greedy choices at each step to ensure that the objective function is optimized. The Greedy algorithm has only one shot to compute the optimal solution so that it never goes back and reverses the decision.

## Algorithm

Step 1: 	Enter the number of cities, places, etc. 
Step 2: 	Prompt the user to enter the distance between each and every city.
Step 3: 	Prompt the user to enter the staring city.
Step 4: 	Repeat step 2, until all cities are done.
Step 5: 	Print the cost matrix, which is a graphical representation of all cities with their distances in a matrix.
Step 6: 	Find the path with the lowest cost or distance, this is an indirect way of calculating the (n-1)! path. 
Step 7: 	Go to the starting city and print it, then mark that city as done.
Step 8: 	Find the minimum valued element in the row corresponding to the city number.
Step 9: 	Print the corresponding city name of that element and mark that city as done.
Step 10: 	Go to the next city, after recording the distance travelled or the cost.
Step 11: 	Go to step 7, until all the rows (cities) are marked as done. 
Step 12: 	After printing the path, print the distance travelled or the total cost of the given path.
