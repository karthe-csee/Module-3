# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
my_tuple = ('a', 'n', 5, 8, 'hello')
if 'n' in my_tuple and 8 in my_tuple:
    print("Both 'n' and 8 exist in the tuple")
elif 'n' in my_tuple:
    print("'n' exists but 8 does not")
elif 8 in my_tuple:
    print("8 exists but 'n' does not")
else:
    print("Neither 'n' nor 8 exist in the tuple")
```
## Output
<img width="418" height="171" alt="image" src="https://github.com/user-attachments/assets/1cc0899b-0c70-49fc-98ba-635d2af1eaa8" />

## Result
Hence the python program is executed sucessfully.
