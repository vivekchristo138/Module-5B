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
```
import pandas as pd
student_data1=pd.DataFrame(eval(input()))
student_data=pd.DataFrame(eval(input()))

print("Original DataFrames:")
print(student_data1)
print("-"*37)
print(student_data)
print()
result_data=pd.concat([student_data1,student_data], axis=1)
print("Join the said two dataframes along columns:")
print(result_data)
```
## Output
<img width="1053" height="747" alt="81" src="https://github.com/user-attachments/assets/a9b113b0-73c4-4db8-af02-88474181dc08" />

## Result
Thus, the Python program using Pandas was successfully executed to join two DataFrames along rows and display the combined DataFrame.


