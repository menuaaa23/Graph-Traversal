# Graph-Traversal
Important note: To receive full credit, submit three files: header file, implementation file and driver (main) file OR at least two files: header and main files.  The depth-first search (DFS) is similar to the preorder traversal of a binary tree. In the case of a tree, the search starts from the root. In a graph, the search can start from any vertex in the graph and visits all vertices in the graph as far as possible before backtracking.  The breadth-first search (BFS) also starts at the root of the tree, but unlike DFS it explores the neighbor nodes first, before moving to the next level neighbors.  In other words, BFS explores vertices in the order of their distance from the source vertex, where distance is the minimum length of a path from source vertex to the node.  You are given the map of 12 cities. The cities can be represented as a string of vertices:  string vertices[] = { "Seattle", "San Francisco", "Los Angeles", "Denver", "Kansas", "Chicago", "Boston", "New York", "Atlanta", "Miami", "Dallas", "Houston"};
Write a C++ program to display the Depth-First Search and Breadth-First Search starting at any vertex (index) inputting from the user.

Sample output:

Graph Traversals
Enter starting city using number from 0 - 11: 2
You entered city name: Los Angeles

Starting at Los Angeles, 12 cities are searched in this Depth-First Search order:
Los Angeles, San Francisco, Seattle, Denver, Kansas, Chicago, Boston, New York, Atlanta, Miami, Houston, Dallas,
Starting at Los Angeles, 12 cities are searched in this Breadth-First Search order:
Los Angeles, San Francisco, Denver, Kansas, Dallas, Seattle, Chicago, New York, Atlanta, Houston, Boston, Miami,

Try another city (Y/N) Y

Enter starting city using number from 0 - 11: 5
You entered city name: Chicago

Starting at Chicago, 12 cities are searched in this Depth-First Search order:
Chicago, Seattle, San Francisco, Los Angeles, Denver, Kansas, New York, Boston, Atlanta, Miami, Houston, Dallas,

Starting at Chicago, 12 cities are searched in this Breadth-First Search order:
Chicago, Seattle, Denver, Kansas, Boston, New York, San Francisco, Los Angeles, Atlanta, Dallas, Miami, Houston,
Try another city (Y/N) N
