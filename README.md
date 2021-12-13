# Binary-Search-Tree
The input for the program is as follows: 

The first line contains a positive integer N, the number of nodes of the initial BST. The second line contains N integers a1,a2,...,an which is the preorder list of the value of nodes in the BST. Then, the test case contains M lines of commands, where it will continue inputting until EOF is met. 

I: The insertion command. The command is followed by an integer input, the desired number to be inserted into the BST.
D: The deletion command. The command is followed by an integer input, the desired number to be deleted from the BST. 
P: The print command. Print the BST in the format  root(left_child_node()())(right_child_node()()).
L: The command estimates the least number of nodes that need to be removed. The command is followed by an integer Vmax, the desired maximum total value of the tree. Output the least number of nodes that need to be removed to make the sum of the tree at most V.
M: The command estimates the most number of nodes that can be removed. The command is followed by an integer Vmin, the desired minimum total value of the tree. Output the most number of nodes that can be removed to make the sum of the tree at least V
