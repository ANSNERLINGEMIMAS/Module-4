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
# Define the dictionary
my_dict = {'apple': 'fruit', 'carrot': 'vegetable', 'banana': 'fruit', 'broccoli': 'vegetable'}

# Sort by keys (alphabetical order of keys)
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort by values (alphabetical order of values)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display the original and sorted dictionaries
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
Original Dictionary: {'apple': 'fruit', 'carrot': 'vegetable', 'banana': 'fruit', 'broccoli': 'vegetable'}
Sorted by Keys: {'apple': 'fruit', 'banana': 'fruit', 'broccoli': 'vegetable', 'carrot': 'vegetable'}
Sorted by Values: {'apple': 'fruit', 'banana': 'fruit', 'carrot': 'vegetable', 'broccoli': 'vegetable'}


## Result
The program sorts the dictionary by keys in alphabetical order and by values in alphabetical order, and then displays both sorted results.

