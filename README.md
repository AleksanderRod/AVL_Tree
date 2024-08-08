Descirption of the code:
The avl.cpp will take inputs from a text file that will command the program to either 
insert or delete a node in a tree or print the entire tree. At every insert and deletion, 
the tree will be run through a balancing function to balance the tree properly using the
AVL tree algorithms. At each insert and deletion, the program will adjust the height of the 
tree accordingly. his consists of a right rotation, left rotation, right-left rotation, and 
a left-right rotation. 

EXTRA CREDIT:
There is also the extra credit function to check if a tree is an AVL tree. This will always
result in being true in my program but if you take away the balancing function in my insert
and or deletion function you will be able to test it and see when the tree is not balanced. 

Use the following command to compile:

$ g++ -std=c++0x avl.cpp

Use the following command to test:

./a.out input1.txt
