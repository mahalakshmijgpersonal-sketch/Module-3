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

lst = ["apple", "cat", "dog", "elephant", "bat"]

result = [x for x in lst if not re.search("e", x)]

print(result)
```
## Output


<img width="222" height="46" alt="image" src="https://github.com/user-attachments/assets/366c527f-ca80-4697-a697-74dd228bd4c8" />

## Result



The program uses regular expressions to filter and display all list elements that do not contain the letter **'e'**.

