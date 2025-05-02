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
    merged_dict = {**dict1, **dict2}  # Merges dict1 and dict2, dict2 overwrites dict1 if keys are the same
    return merged_dict

# Define two dictionaries
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 4, 'd': 5}

# Call the merge function and print the result
merged_result = merge(dict1, dict2)
print("Merged Dictionary:", merged_result)
```

## Output
Merged Dictionary: {'a': 1, 'b': 4, 'c': 3, 'd': 5}


## Result
The program successfully merges the two dictionaries. In case of duplicate keys, the value from dict2 overwrites the one from dict1.
