Types of graphs:
- Undirected Graphs: An undirected graph is a non-directional graph, where each edge connects two vertices and is undirected (there is no concept of direction for the edge).

- Directed Graphs: A directed graph is a graph where every edge is directed. Each directed edge has a direction associated with it, which is specified by an arrow pointing from the tail of the edge to the head of the edge.

- Weighted Graphs: A weighted graph is a graph where each edge has a weight or cost associated with it. The weight of an edge may represent the cost of traversing that edge, or it may represent some other property of the edge.

A graph is a set of vertices or nodes connected by edges or arcs. Edges may be weighted, indicating a cost of traversal. In an undirected graph, all edges are bidirectional. In a directed graph or digraph, all edges are one way.

# Adjacency Matrix
Each row and column represents a node, where the value at its location is its weight. The advantages are that it's convenient to work with, and adding an edge is simple. The disadvantages are that sparse graphs with not many connections (edges) will leave most of the cells empty, wasting a lot of memory space.
A weighted graph can be represented as a dictionary of dictionaries, with each key in the dictionary being the node, and the value being a dictionary of adjacent nodes and edge weights.

# Traversing
## Depth First
With depth-first, you go as far as you can down a path before backtracking and going down the next path. The algorithm uses a stack to keep track of the last node visited, and a list to hold the names of nodes that have been visited.

Applications of depth first include:
- Job-scheduling, where some jobs have to be completed before others can begin.
- Finding a path between two vertices.
- Solving puzzles such as navigating a maze

## Breadth-First
With breadth-first, you explore all the neighbours of the current vertex, then the neighbours of each of those vertices and so on. The algorithm uses a queue to keep track of nodes that still need to be visited.

Applications of breadth first include:
- Finding the shortest path between two points.
- A web crawler uses a breadth first search to analyse sites that you can reach by following links randomly.
- Facebook uses a breadth first search to find all the friends of a given individual.