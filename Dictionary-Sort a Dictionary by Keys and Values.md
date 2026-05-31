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
```p
dictionary = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}

print("Original Dictionary:")
print(dictionary)

sorted_keys = dict(sorted(dictionary.items()))
print("\nDictionary Sorted by Keys:")
print(sorted_keys)

sorted_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))
print("\nDictionary Sorted by Values:")
print(sorted_values)
```
## Sample Output
<img width="1835" height="664" alt="image" src="https://github.com/user-attachments/assets/b15bcbe6-76cf-4147-91f1-5ff76a7a429d" />

## Result
Thus, the Python program to sort a dictionary by keys and values was successfully executed and verified.
