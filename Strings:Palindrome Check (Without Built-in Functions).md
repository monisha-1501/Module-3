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
```
s = "google"

rev = s[::-1]

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## Output
<img width="1397" height="401" alt="{1A155804-138A-4C3D-B3E9-2C1FFC119E76}" src="https://github.com/user-attachments/assets/b5d901f0-d4fc-498d-958f-2a63fc84fff9" />

## Result
The string "google" is not equal to its reverse "elgoog", so it is not a palindrome.
