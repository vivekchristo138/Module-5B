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
```
import numpy as np  
x=[21, 64, 86, 22, 74, 55, 81, 79, 90, 89]
y=[21, 7, 3, 45, 10, 29, 55, 4, 37, 18]
l1=np.array(x) 
l2=np.array(y) 
print(np.where(l1>l2)) 
print(np.where(l1==l2))
```
## Output
<img width="1261" height="281" alt="71" src="https://github.com/user-attachments/assets/b471cb9d-9c27-4c53-b00f-e4f2b7ceb04c" />

## Result
Thus, the NumPy-based array comparison program executed and verified successfully.

