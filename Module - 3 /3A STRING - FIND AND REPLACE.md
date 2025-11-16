# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a python function "convert" to accept a string and converts the uppercase character into lowercase character, lowercase character into uppercase  character and also replace the special characters with "bb".

---

### ALGORITHM

1. Begin the program.
2. Define a function named convert that accepts one string parameter: input_string.
3. Initialize an empty list or string, which will store the characters of the processed result.
4. Iterate through each character (char) in the input_string.
5. For each char, determine if it is a letter using a condition check (e.g., char.isalpha() in Python).
6. If the character is a letter:
      a. Check if the character is uppercase (e.g., char.isupper()).
      b. If it is uppercase, convert it to lowercase and append it to the result list.
      c. Otherwise (if it is lowercase), convert it to uppercase and append it to the result list.
7. If the character is NOT a letter (i.e., a special character, digit, or space):
      a. Append the fixed replacement string "bb" to the result list.
8. After the loop completes, join the elements of the result list back into a single string.
9. Return the final modified string.
10. (Demonstration) Call the convert function with an example string (e.g., "HeLlO 123!") and print the output.
11. Terminate the program.

---

### PROGRAM

```python
def convert(s):
    result = ""
    for char in s:
        if char.isupper():
            result += char.lower()
        elif char.islower():
            result += char.upper()
        else:
            result += "bb"
    print(result)
```

### OUTPUT
<img width="1185" height="281" alt="image" src="https://github.com/user-attachments/assets/bdc34821-293c-4fd2-9669-176ec118af9f" />

### RESULT
Therefore, the outptut is the example to "convert" to accept a string and converts the uppercase character into lowercase character, lowercase character into uppercase  character and also replace the special characters with "bb".
