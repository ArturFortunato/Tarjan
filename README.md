C++ implementation of the Tarjan algorithm to find strong connected components (SCC's) in a directed graph.

Input:
  
    -> A line with the number of nodes (n)
    -> A line with the number of connections between nodes (m)
    -> m lines with 'a b', where a is the origin of the connection and b the end (if the node 3 connects to the node 1, you write '3 1').
    
Output:

    -> A line with the number of scc's
    -> A line with the number of connections between SCC's (maximum 1 connection between 2 SCC's) -> L
    -> L lines with 'a b', where a is the node with the smallest index in the origin SCC and b is the node with the smallest index in the arrival SCC (if an SCC contains <1,2,3> and connects to an SCC that contains <9,4,7>, the program writes '1 4').
    
Example input:


5
6
1 2
2 3
3 1
2 4
5 4
4 5

Correspodent output:

2
1
1 4
