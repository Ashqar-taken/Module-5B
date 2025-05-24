# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
Developed By: Ashqar Ahamed S.T
Register No: 212224240018
```
```
import pandas as pd
student1 = {
    'Name':["Ashqar","Stark","Logan","Viper","Steven","Sheldon"],
    "Age" : [20,21,21,19,19,18],
    "S_id":[1,2,3,4,5,6],
    "Attendance":[82,81,74,84,91,100]
}

student2 = {
    "Name" : ["Eren","Erwin","Mikasa","Armin","Levi","Zeke"],
    "Age" : [18,21,18,18,18,21],
    "S_id": [7,8,9,10,11,12],
    "Attendance": [93,96,93,97,75,81]
}

Student_data1 = pd.DataFrame(student1)
Student_data2 = pd.DataFrame(student2)

Student_data = pd.concat([Student_data1,Student_data2],axis=0)

print("Student Data 1: ")
print(Student_data1)
print("\nStudent Data 2: ")
print(Student_data2)
print("\nStudent Data (concatenated): ")
print(Student_data)
```

## Output

![Screenshot 2025-05-24 221626](https://github.com/user-attachments/assets/307c99a0-f8a0-4dd3-a0d8-06a4592d07a7)

## Result
A Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame was written Successfully.
