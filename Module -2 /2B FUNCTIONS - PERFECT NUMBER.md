# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No-212223060190
#Name:Om Sharma M
#Add your Code Here

def perfectNumber(n):
    factor_sum = 0
    if n <= 1:
        print(f"{n} is not a perfect number.")
        return
    for i in range(1, n // 2 + 1):
        if n % i == 0:
            factor_sum += i
    if factor_sum == n:
        print(f"{n} is a perfect number.")
    else:
        print(f"{n} is not a perfect number.")

a=int(input())
perfectNumber(a)
```
### OUTPUT
<img width="1643" height="599" alt="image" src="https://github.com/user-attachments/assets/aa341b01-4972-46e3-8b4b-6ab1abf939c9" />

<img width="1640" height="605" alt="image" src="https://github.com/user-attachments/assets/c05fa798-1f82-4ecf-bcf1-43611f490eb1" />

### RESULT
Therefore, the output is the example to check if a number is a Perfect number using the concept of functions.
