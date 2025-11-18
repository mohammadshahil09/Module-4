# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
    
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

   
    print(L[4])

except IndexError:
    print("check index range")
```
## Output
<img width="957" height="246" alt="439090813-6c9076bc-1fff-48fb-8d14-1b42c1c9de32" src="https://github.com/user-attachments/assets/9234ef69-081c-4c05-bd71-d98f4abe1d43" />

## Result
Thus the program executed successfully.
