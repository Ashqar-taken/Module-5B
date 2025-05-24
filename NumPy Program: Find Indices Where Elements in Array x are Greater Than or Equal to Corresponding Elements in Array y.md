# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
import numpy as np

a = [12, 34 ,53 ,23, 54, 64, 21, 65, 75]
b = [65, 34, 56, 43, 54, 76, 23, 12, 38]

x = np.array(a)
y = np.array(b)

c = np.where(x>=y)
print("The indices in which x is greater than or equal to is :",c)
```

## Output

![Screenshot 2025-05-24 203734](https://github.com/user-attachments/assets/5aba7f9a-e624-404f-9b8c-80e5c3adac45)

## Result
A Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` was written successfully.
