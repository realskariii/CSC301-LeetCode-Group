# CSC301-LeetCode-Group
Group Work
1. Joseph Ijanu Skari
VUG/SEN/24/11477
2. Isintume ThankGod Kosisochukwu 
VUG/SEN/25/14777
3. Gimba Shurinum Marvellous
VUG/SEN/24/12263
4. Nonso Anya 
VUG/SEN/24/12061
5. Ogwu Matthew Eleojo 
VUG/SEN/24/12057 
6. Desire N. Sam-Imong
VUG/SEN/22/8198
7. Williams James Tobechukwu 
VUG/SEN/24/12635
8. AMU Douglas 
VUG/SEN/24/11220
9. Winner Edoror
VUG/SEN/24/12050



LeetCode Problem #141: Linked List Cycle

Problem Explanation

The Linked List Cycle problem requires us to determine whether a singly linked list contains a cycle.

A cycle occurs when a node points back to an earlier node instead of pointing to "null".

To solve this problem, we use Floyd's Cycle Detection Algorithm, which uses two pointers:

- Slow pointer: Moves one node at a time.
- Fast pointer: Moves two nodes at a time.

If both pointers meet, a cycle exists, and the program returns "true".

If the fast pointer reaches "null", no cycle exists, and the program returns "false".


