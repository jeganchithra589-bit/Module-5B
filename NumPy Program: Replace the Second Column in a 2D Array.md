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
import numpy as np

rows = {'s_id':['S1','S2','S3','S4','S5'],'name':['Dan','Ryder','Bryce','Bernal','Kwame'],'marks':[200, 210, 190, 222,199]}
cols = {'s_id':['S4','S5','S6','S7','S8'],'name':['Scart','Willy','Dani','Kaise','Madeeha'],'marks':[201,200,198,219,201]}


data = []
for i in rows:
    row = list(map(int, input().split()))
    data.append(row)

arr = np.array(data)
print("\nOriginal Array:")
print(arr)

new_col = list(map(int, input("\nEnter elements of new column separated by space: ").split()))
new_col = np.array(new_col)
arr_deleted = np.delete(arr, 1, axis=1)
arr_updated = np.insert(arr_deleted, 1, new_col, axis=1)

print("\nUpdated Array after replacing the second column:")
print(arr_updated)
```
## Output

## Result
