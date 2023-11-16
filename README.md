# EX 03 INVERSE-OF-A-MATRIX
## Date: 16.08.2023
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:import numpy as np

matrix = np.array([[6,  2,  3],
                   [3,  1,  1],
                   [10, 3,  4]])
                   
try:
    inverse = np.linalg.inv(matrix)
    print(inverse)
except np.linalg.LinAlgError:
    print("The matrix is singular and does not have an inverse:")
## Output:
![image](https://github.com/Darkwebnew/INVERSE-OF-A-MATRIX/assets/143114486/75395488-b931-4b20-836b-525373eee84d)

## Result:
Thus the inverse of given matrix is successfully solved using python program

