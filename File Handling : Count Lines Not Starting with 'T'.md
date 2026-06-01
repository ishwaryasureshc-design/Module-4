# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
import io

data = """Today is sunny
Nice weather
Tomorrow will be cloudy
Great dinner"""

file = io.StringIO(data)

count = 0
for line in file:
    if not line.startswith("T"):
        count += 1

print(count)

```

## Output
<img width="1353" height="587" alt="Screenshot 2026-06-01 113902" src="https://github.com/user-attachments/assets/3dbc3dca-a6f2-44ed-9efe-ed64b2d4e77c" />

## Result
The program reads each line from the file story.txt and counts the number of lines that do not start with the character 'T'. After checking all lines, it prints the count.
