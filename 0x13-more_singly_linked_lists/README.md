lists.h: Header file containing definitions and prototypes for all types and functions written for the project.
0-print_listint.c: C function that prints all the elements of a listint_t linked list.
Returns the number of nodes in the listint_t list.
1-listint_len.c: C function that returns the number of elements in a listint_t linked list.
2-add_nodeint.c: C function that adds a new node at the beginning of a listint_t linked list.
If the function fails - returns NULL.
Otherwise - returns the address of the new element.
3-add_nodeint_end.c: C function that adds a new node at the end of a listint_t linked list.
If the function fails - returns NULL.
Otherwise - returns the address of the new element.
4-free_listint.c: C function that frees a listint_t linked list.
5-free_listint2.c: C function that frees a listint_t linked list.
Sets the head to NULL.
6-pop_listint.c: C function that deletes the head node of a listint_t linked list.
If the linked list is empty - returns 0.
Otherwise - returns the head node's data (n).
7-get_nodeint.c: C function that locates a given node of a listint_t linked list.
If the node does not exist - returns NULL.
Otherwise - returns the located node.
8-sum_listint.c: C function that returns the sum of all the data (n) of a listint_t linked list.
If the linked list is empty - returns 0.
Otherwise - returns the sum of all the data (n).
9-insert_nodeint.c: C function that inserts a new node to a listint_t linked list at a given position.
If it is not possible to add the new node at index idx, or the function fails - returns NULL.
Otherwise - returns the address of the new node.
10-delete_nodeint.c: C function that deletes the node at a given index of a listint_t linked list.
If the function succeeds - returns 1.
If the function fails - returns -1.
100-reverse_listint.c** - function that reverses a listint_t linked list with the specifications:
Not allowed to use more than 1 loop
Not allowed to use malloc, free or arrays
Can only declare a maximum of two variables
Returns a pointer to the first node of the reversed list.
101-print_listint_safe.c** - function that prints a listint_t linked list with the specifications:
Can print lists with a loop
Should go through the list only once
If the function fails, exit the program with status 98
Returns the number of nodes in the listint_t list.
102-free_listint_safe.c** - function that frees a listint_t list with the specifications:
Can free lists with a loop
Should go though the list only once
Sets the head to NULL
Returns the size of the list that was freed.
103-find_loop.c** - function that finds the loop in a listint_t list with the specifications:
Not allowed to use malloc, free or arrays
Can only declare a maximum of two variables
If no loop is found - returns NULL.
Otherwise - returns the address of the node where the loop starts.
