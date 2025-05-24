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
Add code here
```
# Step 1: Import the pandas library
import pandas as pd

# Step 2: Create the first DataFrame
student_data1 = {
    'student_id': ['S1', 'S2', 'S3', 'S4'],
    'name': ['Alice', 'Bob', 'Charlie', 'David'],
    'marks': [85, 90, 95, 80]
}
df1 = pd.DataFrame(student_data1)

# Step 3: Create the second DataFrame
student_data2 = {
    'student_id': ['S5', 'S6', 'S7', 'S8'],
    'name': ['Eva', 'Frank', 'Grace', 'Henry'],
    'marks': [75, 88, 92, 79]
}
df2 = pd.DataFrame(student_data2)

# Step 4: Concatenate the DataFrames row-wise (axis=0)
combined
```
## Output
![image](https://github.com/user-attachments/assets/e8418c92-4b50-4e80-a0d6-8d28afc669be)

## Result
The program successfully joins two DataFrames row-wise using pd.concat() and assigns the result to a new DataFrame.
