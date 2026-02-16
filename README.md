# PRACTICAL – 13 (i) Best-First Search (Heuristic-Based Search)

# Aim:

To implement Best-First Search algorithm using heuristic values for AI pathfinding.

# Procedure:

Represent the problem as a graph with nodes and edges.

Assign heuristic values (estimated cost to goal) to each node.

Initialize a priority queue with the start node.

Pop the node with the lowest heuristic from the queue.

Mark it as visited and add its neighbors to the queue based on heuristic.

Repeat until the goal node is reached.

Track visited nodes to avoid cycles.

Display the path and heuristic cost.

Save code for reference.

# Result:
Program executed successfully.

# PRACTICAL – 13 (ii) A* Search Algorithm

# Aim:

To implement the A* Search algorithm using both actual cost and heuristic values for AI pathfinding.

# Procedure:

Represent the problem as a graph with edges and costs.

Assign heuristic values to each node.

Initialize a priority queue with (f = g + h, node) where g = actual cost, h = heuristic.

Pop the node with the lowest f value.

Expand neighbors and calculate their f = g + h.

Track visited nodes to avoid cycles.

Repeat until the goal is reached.

Display the optimal path and total cost.

Compare with Best-First Search.

# Result:
Program executed successfully.
