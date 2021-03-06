# Intro To Graphs

## Basics

Often represented by Vertices (dots).

Connected by Edges (lines)

We can assign weight to edges and vertices.

Adding direction between dots may be important, we can do so by adding directions/edges. If one edge is directed, all need to be directed. If none are directed, they can all be so.

We can add weight to edges. Similar in concept to vectors.

The length of all of the edges does not matter. As long as the edges link the same vertices, it is equal. They will represent the same exact graph.

## Facebook Example

Vertices: Facebook Users (typically represent the data)
Edges: Friendship relationship (or lack thereof), connect User A and B if A&B are friends.

In this case, the friendship relationship is transitive, direction is not needed. Weight is also not necessary, as friendship is a boolean at this point.

Density is the measure of how many edges we have in comparison to the number of vertices we have total.

|V| = # of vertices.

|E| = # of edges.

Density = |E|/(|V| * (|V|-1))

The above formula allows the density to be bound from 0 to 1.

In a directed graph, the number of Ins doubles, also causing the max density to also double to 2.

## Twitter Example

Vertices: Twitter Users
Edges: Follows, Following, Both (Implies Direction is required)

(ie: A ===> B if A is following B)

## Tree Example

A graph can be a tree if it has n vertices, and n-1 Edges

With these conditions, it means we never have any cycles in our tree. It means we'll never start at one vertex and end at the same one.

Tree EX: The DOM itself.
Vertices: DOM elements
Edges: Parent - Children elements

Normally, there would be directions between Parent and Child elements, but in this case it is implied and understood. No need to label it explicitly.
