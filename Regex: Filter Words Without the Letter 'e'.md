

## 🎯 Aim
Write a Python program to find sequences of Upper case letters joined with a '@'.

## 🧠 Algorithm
1.Start
2.Input: A string text from the user or a predefined string.
3.Define Pattern:
    Use a regular expression pattern to match the format:
    One or more uppercase letters, followed by '@', followed by one or more uppercase letters.
    → Pattern: "[A-Z]+@[A-Z]+"
4.Use Regular Expression Module:
   Import the re module.
5.Use re.findall(pattern, text) to find all substrings in text that match the pattern.
6.Store Matches: Save the matched results in a list called matches.
7.Output: Print or return the matches list.
8.End

## 🧾 Program
import re
a=input()
b='[A-Z]+@+[A-Z]'
if re.search(b,a):
    print("Found a match!")
else:
    print("Not matched!")
    
## Output
![image](https://github.com/user-attachments/assets/75815183-6758-440c-803c-dea64eaad7ad)

## Result
This program to find sequences of Upper case letters joined with a '@' is successfully executed.
