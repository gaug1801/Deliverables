# Deliverables
A set of programming assignments to gain experience in algorithms and data structures.

Deliverables is a program that reads in data from a text file to create a bidirectional node graph. 

Example graph in text:
~       val   A   B   C   D   E

Alpha     ~   ~   3   2   ~   5

Bravo     S   4   ~   5   3   ~

Charlie   ~   9   ~   ~   ~   ~

Delta     ~   6   ~   5   ~   1

Echo      G   ~   6   4   2   ~

Code written by me is within the DelivA.java, DelivB.java, DelivC.java, and DelivD.java files.

DelivA calculates the number of node, the number of edges, the node(s) with the most outgoing edges, and the edge(s) with the highest and lowest distance.
DelivB determines the minimum change needed for exact change, implementing both brute force and dynamic programming.
DelivC implements a lowest-cost-first-search algorithm to determine the shortest path to a desired destination from a start city by taking the lowest cost path until reaching the destination.
DelivD takes DelivC another step by doing an A* search to determine the best path to arrive to the desired destination, adding a heuristic value that must be read in as a separate file.

HOW TO RUN (the steps are a bit different for DelivD):

Run the program. A small window will appear.

Select "Read File" and select a node graph from the file browser.

Select "Run Code" and select the desired Deliverable to run.

Results print to the output on the compiler.

RUNNING DELIV D:

Run the program. A small window will appear.

Select "Read File" and select a node graph from the file browser.

Select "Read Heuristic" and select the heuristic graph that matches the graph above.

Select "Run Code" and select the desired Deliverable to run.

Results print to the output on the compiler.







