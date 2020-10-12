#Hacktober-Fest-2020

#Hacktoberfest

Circular Doubly Linked List has properties of both doubly linked list and circular linked list in which two consecutive elements are linked or connected by previous and next pointer and the last node points to first node by next pointer and also the first node points to last node by previous pointer.

Following is representation of a Circular doubly linked list node in C:

// Structure of the node 
struct node
{
    int data;
    struct node *next; // Pointer to next node
    struct node *prev; // Pointer to previous node
};

Advantages of Doubly Linked List
A DLL can be traversed in both forward and backward direction.
The delete operation in DLL is more efficient if pointer to the node to be deleted is given.
We can quickly insert a new node before a given node.
