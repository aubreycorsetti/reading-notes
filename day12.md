# Day 12 Notes

## Trees

### Cheat Sheet

> *Terminology*

• Node - A Tree node is a component which may contain its own values, and references to other nodes

• Root - The root is the node at the beginning of the tree

• K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.

• Left - A reference to one child node, in a binary tree

• Right - A reference to the other child node, in a binary tree

• Edge - The edge in a tree is the link between a parent and child node

• Leaf - A leaf is a node that does not have any children

• Height - The height of a tree is the number of edges from the root to the furthest leaf

### Pseudo

> *Pre-Order Traversal*

ALGORITHM preOrder(root)

  OUTPUT <-- root.value

  if root.left is not NULL
      preOrder(root.left)

  if root.right is not NULL
      preOrder(root.right)

> *In-Order*

ALGORITHM inOrder(root)
// INPUT <-- root node
// OUTPUT <-- in-order output of tree node's values

    if root.left is not NULL
        inOrder(root.left)

    OUTPUT <-- root.value

    if root.right is not NULL
        inOrder(root.right)

> *Post Order*

ALGORITHM postOrder(root)
// INPUT <-- root node
// OUTPUT <-- post-order output of tree node's values

    if root.left is not NULL
        postOrder(root.left)

    if root.right is not NULL
        postOrder(root.right)

    OUTPUT <-- root.value

> *Breadth First Traversal Pseudo*

ALGORITHM breadthFirst(root)
// INPUT  <-- root node
// OUTPUT <-- front node of queue to console

  Queue breadth <-- new Queue()
  breadth.enqueue(root)

  while ! breadth.is_empty()
    node front = breadth.dequeue()
    OUTPUT <-- front.value

    if front.left is not NULL
      breadth.enqueue(front.left)

    if front.right is not NULL
      breadth.enqueue(front.right)

### Big O

• The Big O time complexity for inserting a new node is O(n), same with searching for a specific node.

• The Big O space complexity for a node insertion using breadth first insertion will be O(w)

• The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height)

• The Big O space complexity of a BST search would be O(1)

#### Sources

https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html

#### Things I want to know more about

> I would like to learn more about Big O. I feel like I don't quite have a grasp on it yet.

Click to return [Home!](../README.md)
