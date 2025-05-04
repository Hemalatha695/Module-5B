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
Add code here
```
import numpy as np  # Step 1: Import NumPy

# Step 2: Get input for a 2D array
# For example, you can manually input the array or accept user input
# Here, we'll use a predefined array for simplicity

array = np.array([[34, 23, 12],
                  [1, 90, 32],
                  [78, 54, 11]])

# Step 3: Sort the array column-wise (ascending order)
sorted_array = np.sort(array, axis=0)

# Step 4: Display the original and sorted arrays
print("Original Array:")
print(array)

print("\nColumn-wise Sorted Array:")
print(sorted_array)
```

## Output
```
[[ 1 23 11]
 [34 54 12]
 [78 90 32]]
```
## Result
The program successfully sorts the columns of the 2D NumPy array in ascending order.
