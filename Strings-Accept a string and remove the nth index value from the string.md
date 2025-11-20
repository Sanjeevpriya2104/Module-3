# Module-3(c)
# Strings-Remove Nth Index Character from a String

## Aim
To write a Python program that accepts a string and removes the character at a specified index.

## Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## Program
```
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""   # Empty string to store result

    for i in range(len(s)):
        if i != n:             # Skip the character at index n
            a += s[i]

    return a


# Input from user
string = input("Enter a string: ")

# Calling the function
result = remove(string)

# Printing final output
print("Modified string:", result)
```

## Output
<img width="428" height="178" alt="Screenshot 2025-11-20 145859" src="https://github.com/user-attachments/assets/ece33075-f9b1-4c2a-9b4b-8373caf3feca" />

## Result
programme executed successfully
