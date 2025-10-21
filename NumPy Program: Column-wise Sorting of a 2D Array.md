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
d=eval(input())
arr=np.array(d)
print("Given array")
print(f" {arr}")

print(f"\n{np.sort(arr,axis=0)}")
```

## Output
<img width="784" height="644" alt="Screenshot 2025-10-21 123139" src="https://github.com/user-attachments/assets/d0f784e7-69a6-4b42-a0f6-c56fb3a22fad" />

## Result
successfully created  a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.
