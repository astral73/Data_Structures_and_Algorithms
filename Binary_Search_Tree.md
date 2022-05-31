Binary Search Tree is a node-based binary tree data structure which has the following properties:

- The left subtree of a node contains only nodes with keys lesser than the node’s key.
- The right subtree of a node contains only nodes with keys greater than the node’s key.
- The left and right subtree each must also be a binary search tree.

The Binary Search Tree Stages of a = [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

1) The root will be 7.
2) 5 is less than 7. So, it will be written in left part of 7.
3) 1 is less than 7. Also 1 is less than 5. So, it will be written in left part of 5.
4) 8 is greater than 7. So, it will be written in right part of 7.
5) 3 is less than 7 and less than 5 but 3 is greater than 1. So, it will be written in right part of 1.
6) 6 is less than 7 but 6 is greater than 5. So it will be written in the right part of 5.
7) 0 is less than 7, 5 and 1. So, it will be written in the left part of 1.
8) 9 is greater than 7 and 8. So it will be written in the right part of 8.
9) 4 is less than 7 and 5 but 4 is greater than 1 and 3. So, it will be written in the right part of 3.
10) 2 is less than 7 and 5. Also, 2 is greater than 1 but 2 is less than 3. So, it will be written in the left paprt of 3.

This final result is in this pic:
![Screenshot 2022-05-31 184207](https://user-images.githubusercontent.com/60106930/171216871-5a8cf25e-dc10-4a73-aca0-5537adea1eb2.png)
