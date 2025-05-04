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
Add code here
```
import numpy as np  # Step 1: Import NumPy

# Step 2: Define a 2D NumPy array
original_array = np.array([[1, 2, 3],
                           [4, 5, 6],
                           [7, 8, 9]])

# Define a new column to insert (must match the number of rows)
new_column = np.array([100, 200, 300])

# Step 3: Delete the second column (index 1)
modified_array = np.delete(original_array, 1, axis=1)

# Step 4: Insert the new column at index 1
final_array = np.insert(modified_array, 1, new_column, axis=1)

# Step 5: Print the updated array
print("Original Array:")
print(original_array)

print("\nNew Column to Insert:")
print(new_column)

print("\nUpdated Array After Replacing Second Column:")
print(final_array)
```
## Output
```
Original Array:
[[1 2 3]
 [4 5 6]
 [7 8 9]]

New Column to Insert:
[100 200 300]

Updated Array After Replacing Second Column:
[[  1 100   3]
 [  4 200   6]
 [  7 300   9]]
```
## Result
The program successfully deletes the second column from the original 2D NumPy array and inserts a new column at the same index.
