# GRAPHICAL IMPLEMENTATION OF BINARY SEARCH TREES IN C

The project deals with the Graphical implementation of Binary Search trees for purpose of storing data. This project is intended to register orders made by users for a certain product. The customer who places the highest number of orders should get the delivery first.  The advantage of storing order details in a Binary tree is:

•	To traverse a constructed binary tree takes time complexity of O(N)

•	In order traversal will give the sorted order. 

In normal cases, if BST was not used to store orders. The orders will have to be stored in random order (Linked List) and sorted during delivery (during access) this has the time complexity of O (N*logN). If a sorted list of orders is to be obtained during delivery, accessing all the orders from BST takes just the time complexity of O (N). 

A single Node in BST will have the following part:
1)	Data part to store the number of orders made by the user.
2)	Linked list part, where each node holds the name of the company ordering.
3)	Right Node address part to hold the address of Right child node.
4)	Left Node address part to hold the address of Left Child node.

The user enters the number of orders and the Name of the company placing the order. The number of orders is stored in the data part and the name is stored in the newly created first node of the linked list). If another user makes same number of orders then the numbers of orders will be added to a newly created node in that linked list, which belongs to an existing node of BST which has the same ‘Number of orders’ in its data part. This prevents multiple nodes in BST with the same data part. The insertion of node, deletion of node will be represented graphically on-screen if commands of create and delete are given. Node of BST are represented as a circle with the data part displayed in it and lines connecting two circles represent the connection between the parent and child. The Graphics library in C will be used for accomplishing this.

The graphical implementation of trees can be helpful in implementing ‘Visual Debuggers ’.This is a debugger that shows the creation and destruction of different data structures in a program graphically if the code works properly. However due to logical errors or others, if the graphical view of a particular part of the code of a program is not possible, a bug is identified and also the part of code which caused this is recognised. This helps in error detection and debugging which is much better than the conventional way of debugging. So this allows a graphical view of the implementation of the entire program.
