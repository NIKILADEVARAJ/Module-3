# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(input_string, n):
    # Initialize an empty string to store the result
    a = ""
   for i in range(len(input_string)):
        if i != n:
            a += input_string[i]
    return a
input_string = input("Enter a string: ")
n = int(input("Enter the index of the character to remove: "))
result = remove(input_string, n)
print("Modified string:", result)

```
## Output
![image](https://github.com/user-attachments/assets/916cb2b1-f616-49c0-9d37-b83926043a03)

## Result
The program successfully removes the character at the specified index from the input string and returns the modified string.
