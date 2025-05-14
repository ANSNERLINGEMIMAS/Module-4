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
a={2:56,1:2,5:12,4:24,6:18,3:323}
b=sorted(a.items())
print("Keys and Values sorted in alphabetical order by the key")
for i in b:
    print(i,end=" ")
```

## Sample Output
![Screenshot 2025-05-14 091657](https://github.com/user-attachments/assets/3291b538-bd5a-4a6b-b94f-d71fb8b94753)


## Result
The program sorts the dictionary by keys in alphabetical order and by values in alphabetical order, and then displays both sorted results.

