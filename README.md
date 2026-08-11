# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the numpy library

Step 2: create a matrix using numpy

Step 3: calculate the result using np.linalg.inv

Step 4: End the Program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: P KEERTHANA
#RegisterNumber: 212225230138

import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"
import numpy as np
matrix = np.array([[2,1,1],[1,1,1],[1,-1,2]])
inverse = np.linalg.inv(matrix)
print(inverse)
```
## Output:
![alt text](<Screenshot 2026-08-11 111022.png>)


## Result:
Thus the inverse of given matrix is successfully solved using python program

