# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM

```python
from TreeAVL.AVL import AVL
def getDictTree(self):
    return self.dict_tree
def Construct_AVL(L,n):
    t=AVL(L)
    for i in n:
        t.insertNode(i)
    print(getDictTree(t))
```

## OUTPUT
<img width="1190" height="215" alt="image" src="https://github.com/user-attachments/assets/52675b61-2062-464c-8abf-c6810eec19cc" />

## RESULT
Therefore, the output is the example to write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.
