# GraphsAlgos
Algorithm of DFS, BFS and Dijkstra
These algorithms help to walk om graphs and colloct required in formation about graphs.

#DFS
A standard DFS implementation puts each vertex of the graph into one of two categories:

    1.Visited
    2.Not Visited

The purpose of the algorithm is to mark each vertex as visited while avoiding cycles.

The DFS algorithm works as follows:

    1.Start by putting any one of the graph's vertices on top of a stack.
    2.Take the top item of the stack and add it to the visited list.
    3.Create a list of that vertex's adjacent nodes. Add the ones which aren't in the visited list to the top of the stack.
    4.Keep repeating steps 2 and 3 until the stack is empty.
