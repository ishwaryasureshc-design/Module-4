## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
def merge(dict1, dict2):
    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4, 'e': 5}

merged_dict = merge(dict1, dict2)
print(merged_dict)
```

## Output
<img width="1286" height="662" alt="Screenshot 2026-06-01 113208" src="https://github.com/user-attachments/assets/0e42d3dd-cd6a-483b-8885-3fc15341860d" />

## Result
The program defines two dictionaries, merges them using the ** unpacking operator, and prints the resulting dictionary. If a key is present in both dictionaries, the value from dict2 replaces the value from dict1.
