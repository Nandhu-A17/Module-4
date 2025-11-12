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
~~~
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
~~~
## Output
<img width="500" height="364" alt="image" src="https://github.com/user-attachments/assets/74bc6f47-0d69-4e38-b394-a9b874e1d507" />

## Result
Thus the program was successfully executed.
