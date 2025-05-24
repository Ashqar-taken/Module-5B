# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
Delveloped By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
import numpy as np
rows = int(input("Enter Number of rows: "))
cols = int(input("Enter Number of columns: "))

elements = []
for i in range(rows):
    row = list(map(int, input(f"Row {i+1}: ").split()))
    elements.append(row)

arr = np.array(elements)
print("Original Array: ")
print(arr)

sort_arr = np.sort(arr,axis=0)
print("\nSorted Array: ")
print(sort_arr)
```

## Output

![Screenshot 2025-05-24 203031](https://github.com/user-attachments/assets/9ad83a91-8bd1-4178-89a2-74a089593cfb)

## Result
 a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order was written successfully.
 
