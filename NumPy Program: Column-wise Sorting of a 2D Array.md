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
a=eval(input())
b=np.array(a)
print(f"Given array \n {b}")
print()
print(np.sort(b,axis=0))
```
## Output
<img width="1050" height="762" alt="70" src="https://github.com/user-attachments/assets/cfc32ced-2348-4067-a6a2-a87ef42a8db9" />

## Result
Thus, the Python program using NumPy to perform column-wise sorting of a 2D array has been successfully written, executed, and verified to produce the correct output.


