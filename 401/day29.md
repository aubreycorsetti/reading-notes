# Day 29 Notes

## Graphs

### Cheat Sheet

> Graphs:

• A graph is a non-linear data structure consisting of vertices (nodes) and edges connecting them.

• Vertex: a data object with zero or more adjacent vertices.

• Edge: a connection between two nodes.

• Neighbor: a node connected to another node via an edge.

• Degree: the number of edges connected to a vertex.

• Undirected graph: a graph where each edge is undirected or bi-directional.

• Directed graph (Digraph): a graph where every edge is directed.

• Complete graph: all nodes are connected to all other nodes.

• Connected graph: all vertices/nodes have at least one edge.

• Disconnected graph: some vertices may not have edges.

• Acyclic graph: a directed graph without cycles.

• Cyclic graph: a graph that has cycles.

• Graph representation: Adjacency Matrix or Adjacency List.

> Adjacency List

• Adjacency list is the most common way to represent a graph

• It is a collection of linked lists or arrays that lists all other vertices that are connected to a vertex

• Adjacency lists make it easy to view if one vertex is connected to another

> Weighted Graphs

• Weighted graphs are graphs with numbers assigned to its edges, called weights

•In a weight matrix, the element in the 2D array represents the weight between two vertices

• In an adjacency list representation of a weighted graph, both the weight and name of the adjacent vertex must be included

> Traversals

• In a breadth-first traversal, you start at a specific vertex and visit all the vertices closest to the root before moving outwards

• To traverse a graph, you need to keep track of visited vertices to prevent infinite loop

• The code for breadth-first traversal involves enqueueing the start vertex, adding it to the visited set, and dequeueing the first vertex from the queue. Then, for each unvisited child of the dequeued vertex, add it to the visited set and insert it into the queue. Repeat until the queue is empty.

#### Things I want to know more about

> how to use a graph

#### Sources

[Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

Click to return [Home!](../README.md)
