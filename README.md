# Ford-Fulkerson-Algorithm
 Ford-Fulkerson algorithm finds the maximum flow in a flow network by iteratively augmenting paths from source to sink, adjusting flow values until no augmenting paths exist.

The step by step description for code:

Header Inclusions: Include necessary header files such as <iostream>, <limits.h>, <queue>, and <string.h>.

Namespace: Use the std namespace for standard C++ functions.

Constants: Define the number of vertices V in the graph. Here, V is set to 6.

Function Declaration - bfs: Declare a function bfs to perform Breadth First Search (BFS) in the residual graph. It checks if there is a path from source s to sink t and fills the parent[] array to store the path.

Function Declaration - fordFulkerson: Declare a function fordFulkerson to implement the Ford-Fulkerson algorithm. It takes the graph, source s, and sink t as parameters and returns the maximum flow from s to t in the given graph.

Function Definition - bfs: Implement the BFS function to find if there exists a path from source to sink in the residual graph.

Function Definition - fordFulkerson: Implement the Ford-Fulkerson algorithm. It initializes a residual graph, finds augmenting paths using BFS, updates the residual capacities of the edges, and calculates the maximum flow.

Main Function: In the main function, create the graph given in the example and call the fordFulkerson function with the graph, source vertex 0, and sink vertex 5. Print the maximum possible flow returned by the algorithm.

DEMO:

![image](https://github.com/arshasuresh03/Ford-Fulkerson-Algorithm/assets/160167081/5f493d9b-d6e0-42c0-b217-dbbd0e77a4ee)

![image](https://github.com/arshasuresh03/Ford-Fulkerson-Algorithm/assets/160167081/29e97aec-42e1-4a2e-a115-cd56b99c2e27)

