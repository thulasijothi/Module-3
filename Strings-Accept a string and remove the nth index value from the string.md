# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
Write a python function that accepts a string and removes the 3rd index value from the string.

## 🧠 Algorithm
1.Start
2.Input: Accept a string s.
3.Check String Length:
   If the length of s is less than or equal to 3:
   Return the string as-is (since index 3 doesn’t exist).
4.Else:
  Proceed to the next step.
  Remove Character at Index 3:
5.Use slicing:
  s[:3] gets characters from index 0 to 2.
  s[4:] gets characters from index 4 to the end.
  Concatenate the two slices: s[:3] + s[4:].
6.Return the modified string.
7.End

## 💻 Program
def remove(text):
    if len(text)>3:
        new=text[:3]+text[4:]
    else:
        new=text
    print(new)

## Output
![image](https://github.com/user-attachments/assets/178519b8-4ab5-4d1d-a8f1-8b8273953eab)

## Result
This python function that accepts a string and removes the 3rd index value from the string is successfully executed.
