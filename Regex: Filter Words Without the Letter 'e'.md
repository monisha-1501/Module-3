# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
 ```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print(l1)
```
## Output
<img width="1262" height="442" alt="{68C34189-4125-470D-A0DB-3C8A25B40F16}" src="https://github.com/user-attachments/assets/377d62a9-382f-4444-9744-58172ab52d4c" />

## Result
The program successfully filters out words containing the letter 'e' and prints the remaining words in the list.
