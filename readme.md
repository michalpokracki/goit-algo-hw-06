
# Graph Algorithms Homework

## Task 1: Graph Creation and Visualization

We created a transportation network graph representing a city's metro system. The graph has 6 nodes (stations) and 7 edges (connections).

- **Number of vertices:** 6
- **Number of edges:** 7
- **Degrees of each vertex:** {'A': 2, 'B': 2, 'C': 3, 'D': 3, 'E': 2, 'F': 2}

## Task 2: DFS and BFS Implementation

We implemented Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms to find paths in the graph. Comparing the results:

- **DFS paths from A to F:** [['A', 'B', 'D', 'F'], ['A', 'C', 'D', 'F'], ['A', 'C', 'E', 'F']]
- **BFS paths from A to F:** [['A', 'B', 'D', 'F'], ['A', 'C', 'D', 'F'], ['A', 'C', 'E', 'F']]

Both algorithms find all possible paths, but BFS finds the shortest path in terms of the number of edges first.

## Task 3: Dijkstra's Algorithm

We added weights to the edges and used Dijkstra's algorithm to find the shortest path between all nodes:

- **Shortest path from A to F using Dijkstra's algorithm:** ['A', 'B', 'D', 'F']

This shortest path considers the weights of the edges.

## Repository

The repository contains the full code and this readme file.
