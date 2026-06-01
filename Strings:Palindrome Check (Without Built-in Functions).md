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
rev = ""

for i in s:
    rev = i + rev

if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")

```


## Output

<img width="165" height="38" alt="image" src="https://github.com/user-attachments/assets/790fc04c-aa2b-4855-97e7-2db2f76080ea" />



## Result



The program checks whether the string **"google"** is a palindrome by reversing it and comparing it with the original string. Since both are not equal, **"google" is not a palindrome**.

