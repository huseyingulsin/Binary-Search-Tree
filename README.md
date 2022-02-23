# Binary-Search-Tree
**Binary Search Tree** is a node based binary tree data structure in **Computer Science**.

Time complexity cases of **Binary Search Tree** are:

We check the time complexity of Binary Search Tree with height of binary search tree. So, if you want to see what is the complexity of a BST, you can figure out with O(h). 

**Best Case Complexity O(log n)**

If a Binary Search Tree is balanced, that means height of the binary search tree is *logn*. So complexity becomes **O(logn)**

![balanced](https://user-images.githubusercontent.com/20372673/155138926-2c1261b9-66c4-406e-90e1-fd4ed95a91f3.png)



**Worst Case Complexity O(n)**

If a Binary Search Tree is skewed, that means height of the binary search tree is *n*. So complexity becomes **O(n)**

![skewed](https://user-images.githubusercontent.com/20372673/155138605-04aee64d-f8c1-4736-b160-756909d42dd1.png)



**Average Case Complexity  O(log n)**

Average Case is between Best Case situation and Worst Case situation. Height of the binary search tree is *logn*. So complexity becomes **O(logn)**


**How Binary Search Tree works**

There are 3 important rule that we have to know. 

1 --> All nodes of left subtree must be less than the root node.

2 --> All nodes of right subtree must be more than the root node.

3 --> All nodes can have got maximum of two children.


These rules are used on every node and subtrees.


**Example 1: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

![binary search tree](https://user-images.githubusercontent.com/20372673/155127201-144b7f03-cfd0-49a2-ad73-85b683268243.png)

If you want to fully understand how BST works, you can check the tool which is created by Departmant of Computer Science at San Francisco University: https://www.cs.usfca.edu/~galles/visualization/BST.html 

