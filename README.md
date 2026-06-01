# 1. NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
<img width="325" height="277" alt="Screenshot 2026-06-01 133743" src="https://github.com/user-attachments/assets/01e63a7f-efc4-40e1-87ce-3130d5618c55" />


## Output
<img width="349" height="306" alt="Screenshot 2026-06-01 133752" src="https://github.com/user-attachments/assets/c3631330-eef5-4829-ae1c-630d33afcc43" />


## Result
The execution of the program was successfully done.

# 2. NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

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
<img width="394" height="154" alt="Screenshot 2026-06-01 134243" src="https://github.com/user-attachments/assets/0498255a-95eb-48c6-931f-c54fabbd31a4" />


## Output
<img width="378" height="163" alt="Screenshot 2026-06-01 134251" src="https://github.com/user-attachments/assets/f21c7453-d192-402f-b4df-560225973970" />


## Result
The execution of the program was successfully done.

# 3. NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
<img width="454" height="222" alt="Screenshot 2026-06-01 134725" src="https://github.com/user-attachments/assets/7c78fce3-1ca9-4531-8f9c-80c72f695fbb" />


## Output
<img width="392" height="206" alt="Screenshot 2026-06-01 134735" src="https://github.com/user-attachments/assets/dc64e1f6-30f3-4495-a60b-898d100a9a46" />


## Result
The execution of the program was successfully done.

