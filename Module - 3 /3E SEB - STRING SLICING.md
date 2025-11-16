# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python program to find sequences of Upper case letters joined with a underscore.

---

### ALGORITHM

1. Begin the program.
2. Import the re (Regular Expression) module, as it is the most efficient tool for pattern matching in strings.
3. Define a function named find_uppercase_sequences that accepts one string parameter: text.
4. Define the regular expression pattern required to match the sequence:
   a. The pattern should be ([A-Z]+_[A-Z]+).
   b. [A-Z]+: Matches one or more consecutive uppercase letters.
   c. _: Matches the literal underscore character.
   d. [A-Z]+: Matches one or more consecutive uppercase letters immediately following the underscore.
5. Use the re.findall() method, passing the pattern and the text as arguments. This method returns a list of all non-overlapping matches in the string.
6. Return the list of matched sequences.
7. (Demonstration) Call the function with an example string that contains one or more matching sequences (e.g., "THIS_IS_A_TEST and ANOTHER_EXAMPLE").
8. (Demonstration) Print the resulting list of matches.
9. Terminate the program.

---

### PROGRAM

```python
import re
n=input()
pattern=r'[A-Z]+_[A-Z]+'
if re.fullmatch(pattern,n):
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
<img width="1185" height="238" alt="image" src="https://github.com/user-attachments/assets/82a67428-7226-40a5-8b91-31e69ccda1bc" />

### RESULT
Therefore, the output is the example to write a Python program to find sequences of Upper case letters joined with a underscore.
