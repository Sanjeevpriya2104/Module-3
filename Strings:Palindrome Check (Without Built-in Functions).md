# 3(d) Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

##  Program

```
s = "google"   # given string
rev = ""       # variable to store reverse string

# Reverse the string manually
for char in s:
    rev = char + rev

# Check palindrome
if s == rev:
    print(s, "is a palindrome")
else:
    print(s, "is not a palindrome")
```


## Output
<img width="337" height="153" alt="image" src="https://github.com/user-attachments/assets/002f727a-34a7-4f64-9b6a-13114b2339ea" />

## Result
programme executed successfully
