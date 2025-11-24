# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
def palindrome(a):
    x1=a[::-1]
    if a==x1:
       print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
string =input()
palindrome(string)
```

## Output
<img width="758" height="128" alt="517434332-7f10e1ac-a974-4b5b-a45c-8da3af539447" src="https://github.com/user-attachments/assets/62482b8e-fd85-455b-b93a-4b887a342228" />

## Result
Thus the program executed successfully.
