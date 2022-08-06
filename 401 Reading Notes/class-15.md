# Trees
1. Python Binary Tree

A binary tree is a type of tree data structure where each node contains two child nodes. Each node stores a value, and the children store values based on their position in the tree. A binary search tree is a special kind of binary tree where searching for a specific item is fast and efficient.

2. Implementation

The implementation of a binary tree is simple. We start at the root node and then recursively follow the left and right branches until we reach a leaf node. If the node is not a leaf node, we continue following its left branch and right branch. Once we reach a leaf node, we return the stored value.

3. Example

Let's say we have a binary tree containing the numbers 1-10. Here is how we would implement a binary search tree using python:
```python


def insert(tree, val):


  if len(tree) 0:
    return None


mid (len(tree) + 1) // 2

left insert(tree, val)

right insert(tree, val)
  
  if left! None:
    return left

```