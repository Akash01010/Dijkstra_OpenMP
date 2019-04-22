# Dijkstra_OpenMP
Parallelising Dijkstra shortest path algorithm using OpenMP programming


I have to parallelize Dijkstra algorithm. Dijkstra is a greedy algorithm and main overhead in the algorithm is while it calculates the minimum weight vertex to be explored next. I have parallelized this particular step of calculating minimum of weights of the vertices unexplored. I have also parallelized the updation of the distances of unvisited nodes from the currently explored vertices.

To Run the program:
Step 1: Type gcc -fopenmp -o dijkstra dijkstra.c
Step 2: ./dijkstra
(It will ask to input no of vertices and adjacency matrix and starting node and no. of parallel threads to spawn. One example for testing is provided in the file Test_example.txt. Graph is attached for visual representation of testing example).

It will show the Shortest path from starting node to all other vertices. 
