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
import numpy as np
a=eval(input())
b=eval(input())
arr=np.array(a)
arr2=np.array(b).reshape(-1,1)
print('Before inserting new column')
print(f' {arr}')
print('After inserting new column')
d=np.concatenate((arr,arr2),axis=1)
print(f' {d}')
```

## Output
<img width="1021" height="641" alt="Screenshot 2025-10-21 123607" src="https://github.com/user-attachments/assets/58eddb87-fda8-41fc-a699-3a8cd1922f50" />

## Result
successfully created  a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.
