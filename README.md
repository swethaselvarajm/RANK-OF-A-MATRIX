# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program.
## Program:
```
#Program to find the rank of a matrix.
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
soln=np.linalg.matrix_rank(A)
print(soln)

#Developed by:SWETHA.S
#RegisterNumber:212222230155
```
## Output:
![image](https://github.com/swethaselvarajm/RANK-OF-A-MATRIX/assets/119525603/ac300aee-107b-4ccd-a75e-412b9d87f601)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

