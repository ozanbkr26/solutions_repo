# Problem – Graph Theory and Trees

## Problem Statement
Given a tree with 5 nodes connected as follows:
- A is connected to B and C  
- B is connected to D  
- C is connected to E  

Answer the following:
1. How many edges does the tree have?
2. What is the height of the tree?
3. Is it a binary tree?

## Solution

### 1. Number of Edges
A tree with \( n \) nodes has \( n - 1 \) edges.

So, for 5 nodes:
\[
\text{Edges} = 5 - 1 = 4
\]

### 2. Height of the Tree
- Root: A
- A → B → D → height = 2
- A → C → E → height = 2  
⇒ Max height = **2**

### 3. Binary Tree Check
- Each node has at most 2 children  
⇒ Yes, it's a binary tree.

---

## Visualization

Below is a tree representation of the graph:

![Graph Tree](../../../_pics/graph_tree.png)
