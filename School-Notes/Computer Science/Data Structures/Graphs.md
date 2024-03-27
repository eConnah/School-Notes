Types of graphs:
- Undirected Graphs: An undirected graph is a non-directional graph, where each edge connects two vertices and is undirected (there is no concept of direction for the edge).

- Directed Graphs: A directed graph is a graph where every edge is directed. Each directed edge has a direction associated with it, which is specified by an arrow pointing from the tail of the edge to the head of the edge.

- Weighted Graphs: A weighted graph is a graph where each edge has a weight or cost associated with it. The weight of an edge may represent the cost of traversing that edge, or it may represent some other property of the edge.

A graph is a set of vertices or nodes connected by edges or arcs. Edges may be weighted, indicating a cost oftraversal. In an undirected graph, all edges are bidirectional. In a directed graph or digraph, all edges are one way.

# Adjacency Matrix
Each row and colun represents a node, where the value at its location is its weight. The advantages are that it's convenient to work with, and adding an edge is simple. The disadvantages are that sparse graphs with not many connections (edges) will leave most of the cells empty, wasting a lot of memory space.
A weighted graph can be represented as a dictionary of dictionaries, with each key in the dictionary being the node, and the value being a dictionary of adjacent nodes and edge weights.