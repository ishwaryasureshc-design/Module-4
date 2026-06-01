# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```


## Output
<img width="1324" height="703" alt="Screenshot 2026-06-01 113539" src="https://github.com/user-attachments/assets/08ed44af-7374-45c4-ac66-8e1e67f6037a" />

## Result
The program attempts to access an element at an index that is outside the range of the list. Since the index does not exist, an IndexError occurs, which is caught by the except block, and the custom message is displayed.
