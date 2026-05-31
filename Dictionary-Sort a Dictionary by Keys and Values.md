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
# Sample dictionary
d = {'banana': 'yellow', 'apple': 'red', 'cherry': 'dark red'}

# Sort by keys
sorted_by_keys = dict(sorted(d.items()))
print("Sorted by keys:", sorted_by_keys)

# Sort by values
sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by values:", sorted_by_values)


## Sample Output

<img width="1314" height="330" alt="image" src="https://github.com/user-attachments/assets/6ab650c8-e653-42c7-9865-b825f8c80d0d" />

## Result

The code executed successfully.
