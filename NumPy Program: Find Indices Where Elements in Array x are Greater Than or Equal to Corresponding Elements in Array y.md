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
Add code here
```
import numpy as np  # Step 1: Import NumPy

# Step 2: Define two NumPy arrays
x = np.array([10, 20, 30, 40, 50])
y = np.array([15, 10, 30, 25, 45])

# Step 3: Use Boolean indexing to check where x >= y
indices = np.where(x >= y)[0]  # np.where returns a tuple, use [0] to extract indices

# Step 4: Print the indices where the condition holds true
print("Indices where x >= y:", indices)
```
## Output
```
Indices where x >= y: [1 2 3 4]
```
## Result
This program successfully identifies and prints the indices where the elements of x are greater than or equal to those in y
