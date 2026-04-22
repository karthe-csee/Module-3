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
text = "google"
reversed_text = ""
for char in text:
    reversed_text = char + reversed_text
if text == reversed_text:
    print("Palindrome")
else:
    print("Not a palindrome")
```
## Output
<img width="372" height="179" alt="image" src="https://github.com/user-attachments/assets/b52d2bca-7371-425a-9387-e99b69c55ad2" />
## Result
Hence the python program is executed sucessfully
