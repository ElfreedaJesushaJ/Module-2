# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
from math import factorial
n=int(input())
for i in range(n):
    for j in range(n-i-1):
        print(end=" ")
    for j in range(i+1):
        print(factorial(i)//(factorial(j)*factorial(i-j)),end=" ")
    print()

```

## Sample Output
![Screenshot 2025-04-29 141431](https://github.com/user-attachments/assets/16d2d09d-9d13-4d0c-adce-09a822373f62)


## Result
  A Python program that generates **Pascal's Triangle** using numbers,is successfully executed.

