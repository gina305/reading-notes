# Big O: Analysis of Algorithm Efficiency

Big O(oh) notation is used to describe the efficiency of an algorithm or function based on 2 factors:
* Running Time (also known as time efficiency / complexity)- The amount of time a function needs to complete.
* Memory Space (also known as space efficiency / complexity) - The amount of memory resources a function uses to store data and instructions.

The Big O describes the worse case scenario for a function and algorithm to complete in regards to time and space (memory.) Factors that affect time and or space include: 
* Input Size - the size of the parameter values.   Represented by the variable n, the total size of values used as parameters in an algorithm
* Units of Measurement
* Orders of Growth -  the Order of Growth represents the increase in Running Time or Memory Space.
* Best Case, Worst Case, and Average Case


![](imgs/img_3.png)

# Linked Lists

A Linked List is a sequence of Nodes that are connected/linked to each other.  Each node has a next property that determines which node is next in the link. A linked list contains a head reference and a current reference. The head reference identified the first node in the list. The current reference refers to the node that is currently being looked at.


There are two types of Linked List - Singly and Doubly
* Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
* Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
____

References: 
* Big O Notation: https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html
* Linked Lists: https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html
