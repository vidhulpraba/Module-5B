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
import numpy as np

arr = np.array([[9, 2, 7],
                [4, 8, 1],
                [6, 3, 5]])

result = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Array after sorting each column:")
print(result)
```
## Output
Original Array:
[[9 2 7]
 [4 8 1]
 [6 3 5]]

Array after sorting each column:
[[4 2 1]
 [6 3 5]
 [9 8 7]]
## Result
### NumPy Program

```python id="58347"
import numpy as np

arr = np.array([[9, 2, 7],
                [4, 8, 1],
                [6, 3, 5]])

result = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Array after sorting each column:")
print(result)
```

### Output

```text
Original Array:
[[9 2 7]
 [4 8 1]
 [6 3 5]]

Array after sorting each column:
[[4 2 1]
 [6 3 5]
 [9 8 7]]
```

**Result:**
Thus, the NumPy program to sort the elements in each column of a 2D array in ascending order was successfully executed.
