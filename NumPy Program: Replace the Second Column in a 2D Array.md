# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
Developed By: Ashqar Ahamed S.T
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

print("Enter a value for a new column(a single value for each row): ")
new_col = []
for l in range(rows):
    row = list(map(int, input(f"{l+1}: ").split()))
    new_col.append(row)


arr = np.array(elements)
col = np.array(new_col)

arr_deleted = np.delete(arr,1,axis=1)
arr_insert = np.insert(arr_deleted,1,col,axis=1)

print("Original Array: ")
print(arr)
print("\nThe deleted array: ")
print(arr_deleted)
print("\nNewly Inserted Array: ")
print(arr_insert)
```

## Output

![Screenshot 2025-05-24 210857](https://github.com/user-attachments/assets/b0b609e0-9e17-4d04-84f0-b05728cc606d)

## Result
a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position was written successfully.
