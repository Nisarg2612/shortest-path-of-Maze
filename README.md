# shortest-path-of-Maze
Find the shortest path of maze using Bellman Ford's Algorithm

![image](https://user-images.githubusercontent.com/35762778/145765437-3d0b8e79-099a-4ed8-b031-35cea63ce4c4.png)

**Bellman Ford's Algorithm**

The algorithm calculates shortest path in a bottom-up manner. It start calculating the shortest distances which have at-most one edge in the path. Then, it calculates the shortest path with at-most two edges, and so on. After the i-th iteration of the outer loop, the shortest path with most i edged are calulated. The algorithm runs until the minimum cost is not changed for a cycle or |v -1| iteration reached. The idea is, assuming that there is no negative weight cycle, if we have calculated shortest paths with at most i edges, then an iteration over all edges guarantees to give shortest path with at-most (i+1) edge.

The time complexity of Bellman Ford's algorithm is **O(V * E)**

**Learning Outcome**
1. Illustrate how to convert maze into spanning tree
2. Understand the how to calculate the distance between two nodes.
3. Identify the shortest path between two vertices.
4. Examine the performance of Bellman Ford's algorithm. 

Google slides presentation link
https://docs.google.com/presentation/d/1i4exgwrzGyveCHqzhouyNBL0Yp3IZ09v8EU8iqiNVP0/edit?usp=sharing
