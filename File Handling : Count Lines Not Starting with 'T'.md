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
# Open the file in read mode
with open('story.txt', 'r') as file:
    count = 0
    # Iterate through each line in the file
    for line in file:
        # Check if the line does not start with 'T'
        if not line.startswith('T'):
            count += 1

# Print the result
print("Number of lines that do not start with 'T':", count)
```

## Output
![WhatsApp Image 2025-05-21 at 13 59 04_77f479fd](https://github.com/user-attachments/assets/537ade25-c65f-49a4-854d-74f418019ed3)



## Result
The program successfully counts and prints the number of lines in story.txt that do not start with the letter 'T'. The file is processed line by line, and the count is updated accordingly.

