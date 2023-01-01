# GraphsAlgos
Algorithm of DFS, BFS and Dijkstra
These algorithms help to walk om graphs and colloct required in formation about graphs.

# DFS
A standard DFS implementation puts each vertex of the graph into one of two categories:

    1.Visited
    2.Not Visited

The purpose of the algorithm is to mark each vertex as visited while avoiding cycles.

The DFS algorithm works as follows:

    1.Start by putting any one of the graph's vertices on top of a stack.
    2.Take the top item of the stack and add it to the visited list.
    3.Create a list of that vertex's adjacent nodes. Add the ones which aren't in the visited list to the top of the stack.
    4.Keep repeating steps 2 and 3 until the stack is empty.

# BFS
Breadth-first search is a graph traversal algorithm that starts traversing the graph from the root node and explores all the neighboring nodes. Then, it selects the nearest node and explores all the unexplored nodes. While using BFS for traversal, any node in the graph can be considered as the root node.

There are many ways to traverse the graph, but among them, BFS is the most commonly used approach. It is a recursive algorithm to search all the vertices of a tree or graph data structure. BFS puts every vertex of the graph into two categories - visited and non-visited. It selects a single node in a graph and, after that, visits all the nodes adjacent to the selected node.

    Step 1: SET STATUS = 1 (ready state) for each node in G
    Step 2: Enqueue the starting node A and set its STATUS = 2 (waiting state)
    Step 3: Repeat Steps 4 and 5 until QUEUE is empty
    Step 4: Dequeue a node N. Process it and set its STATUS = 3 (processed state).
    Step 5: Enqueue all the neighbours of N that are in the ready state (whose STATUS = 1) and set
    their STATUS = 2
    (waiting state)
    [END OF LOOP]
    Step 6: EXIT
