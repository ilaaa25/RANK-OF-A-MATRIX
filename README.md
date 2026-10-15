# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: ILAMARAN M
#RegisterNumber: 26018720
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
sol=np.linalg.matrix_rank(a)
print(sol)
```
## Output:<img width="1341" height="812" alt="Screenshot 2026-10-15 220850" src="https://github.com/user-attachments/assets/90ef3592-9d2c-418a-8e3a-4110865e307c" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

