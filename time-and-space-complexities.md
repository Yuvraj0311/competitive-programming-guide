# 📘 Time and Space Complexities — DSA Cheat Sheet

This document summarizes the time and space complexities for data structures and algorithms commonly used in competitive programming and coding interviews. Organized by topic for quick reference.

---

## ✅ Arrays & Strings

| Algorithm / Operation         | Time Complexity     | Space Complexity |
|------------------------------|---------------------|------------------|
| Access / Traversal           | O(1) / O(n)         | O(1)             |
| Two-pointer techniques       | O(n)                | O(1)             |
| Sliding Window               | O(n)                | O(1)             |
| Prefix Sum / Difference Array| O(n) + O(1) query   | O(n)             |
| Kadane’s Algorithm           | O(n)                | O(1)             |
| KMP Algorithm                | O(n + m)            | O(m)             |
| Rabin-Karp                   | O(n + m) avg        | O(1) to O(n)     |

---

## ✅ Hashing

| Structure / Use Case         | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| HashMap / HashSet (avg)     | O(1)                | O(n)             |
| HashMap (worst)             | O(n)                | O(n)             |
| Frequency Counter           | O(n)                | O(n)             |

---

## ✅ Stack & Queue

| Operation / Algorithm        | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Push / Pop / Front / Back   | O(1)                | O(n)             |
| Monotonic Stack             | O(n)                | O(n)             |
| Next Greater Element        | O(n)                | O(n)             |
| Queue using 2 Stacks        | O(1) or O(n)        | O(n)             |
| Sliding Window Maximum      | O(n)                | O(k)             |

---

## ✅ Linked List

| Operation                    | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Access                      | O(n)                | O(1)             |
| Insert/Delete at head/tail | O(1)                | O(1)             |
| Detect Cycle (Floyd’s)     | O(n)                | O(1)             |
| Reverse Linked List        | O(n)                | O(1)             |
| Merge Sort on LL           | O(n log n)          | O(log n)         |

---

## ✅ Trees

| Algorithm / Operation        | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| DFS / BFS Traversal         | O(n)                | O(h)             |
| Diameter of Tree            | O(n)                | O(h)             |
| LCA (Binary Tree)           | O(n)                | O(h)             |
| BST Operations              | O(h) avg, O(n) worst| O(h)             |
| Segment Tree (Build/Query)  | O(n), O(log n)      | O(n)             |
| Fenwick Tree (BIT)          | O(log n)            | O(n)             |

---

## ✅ Heap / Priority Queue

| Operation                    | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Insert / Delete / Top       | O(log n)            | O(n)             |
| Heapify                     | O(n)                | O(1)             |
| Kth Largest / Smallest      | O(n log k)          | O(k)             |

---

## ✅ Recursion & Backtracking

| Problem                      | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| N-Queens / Sudoku Solver     | Exponential         | O(N^2)           |
| Subsets / Permutations       | O(2^n * n) / O(n!)  | O(n)             |
| General Backtracking         | Exponential         | O(path length)   |

---

## ✅ Dynamic Programming

| Pattern / Problem            | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Memoization (Top-down)      | O(states)           | O(states)        |
| Tabulation (Bottom-up)      | O(n), O(n^2), etc.  | O(n), O(n^2)     |
| 0/1 Knapsack                | O(n * W)            | O(n * W)         |
| LCS / Edit Distance          | O(n * m)            | O(n * m)         |
| LIS (with BS)               | O(n log n)          | O(n)             |

---

## ✅ Greedy Algorithms

| Algorithm                    | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Activity Selection           | O(n log n)          | O(1)             |
| Huffman Coding               | O(n log n)          | O(n)             |
| Fractional Knapsack          | O(n log n)          | O(1)             |

---

## ✅ Graph Algorithms

| Algorithm                    | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| DFS / BFS                   | O(V + E)            | O(V)             |
| Topological Sort (DFS/Kahn) | O(V + E)            | O(V)             |
| DSU (Path Compression + Rank)| O(α(n)) per op     | O(n)             |
| Dijkstra (PQ)               | O((V + E) log V)     | O(V)             |
| Bellman-Ford                | O(VE)               | O(V)             |
| Floyd-Warshall              | O(V^3)              | O(V^2)           |
| Kruskal’s MST               | O(E log E)          | O(V)             |
| Prim’s MST (Min Heap)       | O(E log V)          | O(V)             |
| Kosaraju’s SCC              | O(V + E)            | O(V)             |
| Tarjan’s SCC                | O(V + E)            | O(V)             |
| Bridges / Articulation Points | O(V + E)          | O(V)             |

---

## ✅ Tries & String Algorithms

| Algorithm                    | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Trie Insert / Search        | O(L)                | O(n * L)         |
| Aho-Corasick                | O(n + m + z)        | O(n)             |
| Suffix Array                | O(n log n)          | O(n)             |
| Suffix Tree                 | O(n)                | O(n)             |

---

## ✅ Bit Manipulation

| Operation / Problem          | Time Complexity     | Space Complexity |
|-----------------------------|---------------------|------------------|
| Count Set Bits              | O(log n)            | O(1)             |
| Bitmask Subset Gen          | O(2^n)              | O(n)             |
| XOR Problems                | O(n)                | O(1)             |


