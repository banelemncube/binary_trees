Learning Objectives💡
What you should learn from this project:

What is a binary tree
What is the difference between a binary tree and a Binary Search Tree
What is the possible gain in terms of time complexity compared to linked lists
What are the depth, the height, the size of a binary tree
What are the different traversal methods to go through a binary tree
What is a complete, a full, a perfect, a balanced binary tree
Data structures
Basic Binary Tree
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
Binary Search Tree
typedef struct binary_tree_s bst_t;
AVL Tree
typedef struct binary_tree_s avl_t;
Max Binary Heap
typedef struct binary_tree_s heap_t;
0. New node
Write a function that creates a binary tree node
1. Insert left
Write a function that inserts a node as the left-child of another node

2. Insert right
All your files, classes, functions must be tested with unit tests
3. Delete
Write a function that deletes an entire binary tree
4. Is leaf
Write a function that checks if a node is a leaf
5. Is root
Write a function that checks if a given node is a root
6. Pre-order traversal
Write a function that goes through a binary tree using pre-order traversal
7. In-order traversal
Write a function that goes through a binary tree using in-order traversal
8. Post-order traversal
Write a function that goes through a binary tree using post-order traversal
9. Height
Write a function that measures the height of a binary tree
10. Depth
Write a function that measures the depth of a node in a binary tree
11. Size
Write a function that measures the size of a binary tree
12. Leaves
Write a function that counts the leaves in a binary tree
13. Nodes
Write a function that counts the nodes with at least 1 child in a binary tree
14. Balance factor
Write a function that measures the balance factor of a binary tree
15. Is full
Write a function that checks if a binary tree is full
16. Is perfect
Write a function that checks if a binary tree is perfect
17. Sibling
Write a function that finds the sibling of a node
18. Uncle
Write a function that finds the uncle of a node
19. Lowest common ancestor
Write a function that finds the lowest common ancestor of two nodes
20. Level-order traversal
Write a function that goes through a binary tree using level-order traversal
21. Is complete
Write a function that checks if a binary tree is complete
22. Rotate left
Write a function that performs a left-rotation on a binary tree
23. Rotate right
Write a function that performs a right-rotation on a binary tree
24. Is BST
Write a function that checks if a binary tree is a valid Binary Search Tree
25. BST - Insert
Write a function that inserts a value in a Binary Search Tree
26. BST - Array to BST
Write a function that builds a Binary Search Tree from an array
27. BST - Search
Write a function that searches for a value in a Binary Search Tree
29. Big O #BST
Average time complexities of insert, delete, search for BST
