Kruskal Algorithm for Minimum Spanning Tree
Minimum Spanning Tree: A MST for a weighted connected undirected graph is the spanning tree whose total weight is less than the total weights of all the spanning tree possible 

Input:Graph
Output:MST
Algorithm:
Step 1 -> First we have to sort all the edges in the increasing order of their weights.
Step 2 -> Take the smallest weighted vertex and checks if it forms a cycle using Disjoint Set Union(DSU) Data Structure .If it doesnot form a cycle include it in the MST and if it forms a cycle reject it.
Step 3 -> Repeat Step 2 till there are (V-1) edges in the MST.
