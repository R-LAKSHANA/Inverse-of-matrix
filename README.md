# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2:
Get input from the user for number of rows and columns.
### Step 3:
Create empty lists.
### Step 4:
Using nested for() loop to get the matrix from user.
### Step 5:
Assign the matrix in np.array()
### Step 6:
Using the np.linalg.inv(), we can find the inverse of the matrix.
### Step 7:
End the program

## PROGRAM:
```python
'''
Program to find the inverse of a matrix.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
import numpy as np
r,c = int(input()), int(input())
l1,l2 = [],[]
for i in range(r):
    for j in range(c):
        l1.append(int(input()))
    l2.append(l1)
    l1 = []
print(l2)
array1 = np.array(l2)
array_inverse = np.linalg.inv(array1)
print(array_inverse)
```

## OUTPUT:

![output](/Output.png)

## RESULT:
Thus the program to find the inverse of a matrix is written and verified using python
programming.
