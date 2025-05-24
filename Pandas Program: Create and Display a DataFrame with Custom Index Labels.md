# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
import numpy as np
import pandas as pd

exam_data = {'name':["Ashqar","Ayisha","Manish","Santhosh","Longan","stark"],
             'score':[89,92,74,82,35,99],
             'attempts':[1,1,2,1,3,1],
             'qualify':['pass','pass','pass','pass','fail','pass']
             }
labels = ['Student-1','Student-2','Student-3','Student-4','Student-5','Student-6']

df = pd.DataFrame(exam_data,index=labels)

print("The DataFrame: \n",df)
```

## Output

![Screenshot 2025-05-24 215710](https://github.com/user-attachments/assets/c7362da3-0d7e-429b-ae03-b4f4adf60a7c)

## Result
A **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows was created and displayed successfully.
