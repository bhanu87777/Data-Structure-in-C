Following are the content of my Projects:

1. Stack: Implementation using Array and Linked List
Definition: A stack is a linear data structure that follows the Last In, First Out (LIFO) principle. The last element added to the stack is the first one to be removed.

Operations:
Push(): Add an element to the top of the stack.
Pop(): Remove the top element from the stack.
Peek(): View the top element without removing it.
isEmpty(): operation checks whether the stack is empty.
isFull(): operation checks wheather the stack is full.

3. Queue: Implementation using Array and Linked List
Definition: A queue is a linear data structure that follows the First In, First Out (FIFO) principle. The first element added to the queue is the first one to be removed.

Operations:
Enqueue(): Add an element to the rear of the queue.
Dequeue(): Remove an element from the front of the queue.
Peek(): View the front element without removing it.
isEmpty(): operation checks whether the queue is empty.
isFull(): operation checks wheather the queue is full.

Types:
a. Linear Queue: A linear queue is a straightforward implementation of the queue data structure where elements are added at the rear and removed from the front. It follows the First-In-First-Out (FIFO) principle.
b. Circular Queue: A circular queue is a more efficient version of the linear queue where the last position is connected to the first position, forming a circle. This eliminates the problem of wasted space in linear queues.
c. Priority Queue: A priority queue is a special type of queue where each element is associated with a priority, and elements are dequeued based on their priority rather than their position in the queue.
d. Double Ended Queue: A double-ended queue (deque) is a versatile data structure that allows insertion and deletion of elements from both the front and the rear of the queue.

3. Linked List:
Definition: A linked list is a linear data structure where elements (nodes) are stored in a sequence. Each node contains a data element and a reference (or pointer) to the next node in the sequence.
Types:
Singly Linked List: Each node points to the next node.
Doubly Linked List: Each node points to both the next and previous nodes.
Circular Linked List: The last node points back to the first node, forming a circle.
Doubly Circular Linked List: A Doubly Circular Linked List is a variant of a doubly linked list where the last node points back to the first node, and the first node's previous pointer points back to the last node.

Operations:
CreateNode(): Initializes a new node with given data and sets up initial pointers.
Display(): Traverses and prints the elements of the list.
InsertBeginning(): Adds a new node at the beginning of the list.
InsertEnd(): Adds a new node at the end of the list.
InsertPosition(): Inserts a new node at a specified position in the list.
DeleteBeginning(): Removes the node from the beginning of the list.
DeleteEnd(): Removes the node from the end of the list.
DeletePosition(): Deletes a node from a specified position in the list.
Reverse(): Reverses the order of nodes in the list.
Length(): Computes and returns the number of nodes in the list.
Concatenation(): Merges two lists into a single list.
Merge(): Combines two sorted lists into a single sorted list.

6. Tree:
Definition: A tree is a hierarchical data structure consisting of nodes connected by edges. Each node contains a value, and nodes are connected in parent-child relationships.
Types:
Binary Tree: Each node has at most two children.
Binary Search Tree (BST): A binary tree with the property that the left child is smaller and the right child is larger than the parent node.
AVL Tree: A self-balancing binary search tree.
Heap: A complete binary tree used for heap-based priority queues.

7. Graph:
Definition: A graph is a collection of nodes (vertices) connected by edges. Graphs can be either directed (edges have a direction) or undirected (edges are bidirectional).
Types:
Undirected Graph: Edges do not have a direction.
Directed Graph (Digraph): Edges have a direction.
Weighted Graph: Edges have weights representing costs or distances.
Connected Graph: There is a path between any two vertices.

8. Hashing:
Definition: Hashing is a technique used to map data to a fixed-size integer (hash code) which can then be used to index into an array (hash table) for fast data retrieval.
Methods:
Division Method: The hash function is h(k) = k % m, where k is the key and m is the size of the hash table.
Multiplication Method: The hash function involves multiplying the key and extracting bits.
Chaining: Handles collisions by storing multiple elements at the same index using linked lists.
Open Addressing: Handles collisions by finding another open slot within the hash table.
