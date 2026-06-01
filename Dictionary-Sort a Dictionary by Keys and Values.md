# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
my_dict = {'b': 3, 'a': 1, 'd': 4, 'c': 2}

print(dict(sorted(my_dict.items())))                 # sort by keys
print(dict(sorted(my_dict.items(), key=lambda x: x[1])))  # sort by values
```

## Sample Output
<img width="1365" height="615" alt="Screenshot 2026-06-01 113405" src="https://github.com/user-attachments/assets/47af9f61-872b-4ea3-9c85-7d72fc875b6c" />

## Result
The program sorts the dictionary keys in alphabetical order and also sorts the dictionary values in alphabetical order, then displays the sorted results.
