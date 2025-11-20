# 3(b) Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program
```
import re

l1 = []   # Empty list to store results

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:
    if not re.search(r"e", i):   # Check if 'e' is NOT present
        l1.append(i)

print("Filtered list:", l1)

```
## Output
<img width="444" height="159" alt="Screenshot 2025-11-20 145319" src="https://github.com/user-attachments/assets/262a583b-c8b1-4609-9435-4e1e8878e341" />


## Result
programme executed successfully
