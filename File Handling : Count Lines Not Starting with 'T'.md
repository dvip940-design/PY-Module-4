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
```p
story = """The sun rises in the east.
Apple is a fruit.
Today is Monday.
Banana is yellow.
Tiger is a wild animal.
"""

count = 0

for line in story.split('\n'):
    if line != "" and line[0] != 'T':
        count += 1

print("Number of lines not starting with 'T':", count)
```

## Output
<img width="1842" height="522" alt="image" src="https://github.com/user-attachments/assets/13e898cc-ff78-4e45-8d01-4e94601fee4c" />

## Result
Thus, the Python program to count the number of lines in story.txt that do not start with the letter 'T' was successfully executed and verified.
