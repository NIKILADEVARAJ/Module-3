# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'b', 'n', 3, 5, 8)
check_n = 'n' in x
check_8 = 8 in x
print(f"Is 'n' in the tuple? {check_n}")
print(f"Is 8 in the tuple? {check_8}")

## Output
![image](https://github.com/user-attachments/assets/d74d98b3-bbc0-4744-a903-9c5e710db996)

## Result
The program was successfully executed and correctly verified that both 'n' and 8 exist in the given tuple.
