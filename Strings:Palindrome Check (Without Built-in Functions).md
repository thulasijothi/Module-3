# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
a=input()
b=str(a[::-1])
if a==b:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")

## Output
![image](https://github.com/user-attachments/assets/f5ead126-26d2-4ada-8731-222657c546e4)

## Result
This program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is successfully executed.
