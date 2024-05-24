A* search can be applied in network routing algorithms to find the optimal path for data packets
to travel through a computer network, considering metrics such as latency, bandwidth, and
reliability. In figure 2. the simplified graph illustrates a small network topology where routers are
interconnected.
Nodes represent routers (A, B, C, D, E, F). Edges represent connections between routers. The
direction of edges is from A to B D E F or A to C F represents the direction of data flow. Each
edge may have associated metrics such as latency, bandwidth, or cost.


![image](https://github.com/rohit546/A_Star_Search_AI_Algorithm-Python-/assets/100420859/7b88946b-58e7-4c85-a4dc-5cbfc5bbfa79)

Router A value from start node is 0.
Router B value from A to B is 3
Router C value from A to C is 3
Router D value from A to D is 5
Router E value from A to E is 4
Router F value from A to F is 0
Use Manhattan distance to calculate the heuristic values for each node.
Calculate time complexity, space complexity and complete path to reach the goal.
Plot the graph of the complete path using library network and matplotlib.
