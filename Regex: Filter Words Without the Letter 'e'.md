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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
l1,l2=[],[]
for i in items:
    for x in i:
        if x=="e":
            l1.append(i)
            break
for a in items:
    if a not in l1:
        l2.append(a)
print(l2)


```
## Output
<img width="963" height="223" alt="image" src="https://github.com/user-attachments/assets/45d49cdd-f506-4a69-ba1f-b70175009196" />



## Result
programme executed successfully
