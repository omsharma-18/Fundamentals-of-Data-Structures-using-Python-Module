# Ex. No: 16B - Constructing and Balancing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree**, balance it, and print the nodes **before and after balancing** using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a method `getDictTree(tree)` to return the `dict_tree` or structure of the AVL tree.

**Step 3**: Define a method `Construct_AVL(L)` to:
- Create a binary tree from the list `L`.
- Print the tree **before balancing**.
- Sort and reinsert the nodes in a balanced manner (simulating AVL behavior).
- Print the tree **after balancing**.

**Step 4**: Create a list `L` of integers.

**Step 5**: Call `Construct_AVL(L)` to build and balance the tree.

**Step 6**: End the program.

---

## PYTHON PROGRAM

```python
from TreeAVL.AVL import AVL
def Construct_AVL(L):
    t=AVL(L)
    print("Length of an AVL Tree is",t.length_tree)
```

## OUTPUT
<img width="1185" height="195" alt="image" src="https://github.com/user-attachments/assets/27a79949-5df9-4bb4-96cc-8de7dc4b2ee8" />

## RESULT
Therefore, the output is the example to write a Python program to construct an **AVL tree**, balance it, and print the nodes **before and after balancing** using the appropriate packages and built-in function.
