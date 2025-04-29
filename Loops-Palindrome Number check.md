## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num=int(input())
rev=0
temp=num
while temp>0:
    rev=rev*10
    rev=rev+temp%10
    temp//=10
if(num==rev):
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

```

## Output
![Screenshot 2025-04-29 141938](https://github.com/user-attachments/assets/cc44b871-5634-433b-b711-1aff1f43e9fa)

## Result
     A Python program that checks whether a given number is a **palindrome** using loops,is successfully executed
