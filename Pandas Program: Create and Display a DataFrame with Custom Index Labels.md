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
Add code here
```
# Step 1: Import libraries
import pandas as pd
import numpy as np

# Step 2: Create dictionary with data
exam_data = {
    'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily'],
    'score': [12.5, 9.0, 16.5, np.nan, 9.0],
    'attempts': [1, 3, 2, 3, 2],
    'qualify': ['yes', 'no', 'yes', 'no', 'no']
}

# Step 3: Create index labels
labels = ['a', 'b', 'c', 'd', 'e']

# Step 4: Create DataFrame
df = pd.DataFrame(exam_data, index=labels)

# Step 5: Display DataFrame
print("DataFrame Output:")
print(df)
```


## Output
![image](https://github.com/user-attachments/assets/35d40046-f20c-4318-ae10-1e870bb285e4)

## Result
The program successfully creates and displays a Pandas DataFrame using the provided dictionary and applies the specified row index labels ('a' to 'e'). The score column demonstrates how NaN values are handled (for missing data like in James's case).
