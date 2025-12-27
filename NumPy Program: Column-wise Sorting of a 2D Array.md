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
import numpy as np 

a=np.array(eval(input())) 

print("Given array") 

print(end=" ") 

print(a) 

print() 

print(np.sort(a,axis=0))
```

## Output
<img width="734" height="320" alt="image" src="https://github.com/user-attachments/assets/b84c66e0-83a2-45b7-aaec-d044117c1220" />

## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.
