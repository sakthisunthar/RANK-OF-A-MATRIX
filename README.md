# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy module to use mathematical and matrix functions.
### Step 2: Create a matrix using np.array() and store it in a variable A.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the value of X to display the rank of the matrix.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: sakthi sunthar k k
#RegisterNumber:212225040361
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=([[5,-3,-10],[2,2,-3],[-3,-1,5]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
<img width="1272" height="761" alt="image" src="https://github.com/user-attachments/assets/c8927339-7c64-4729-8337-6f3e69215ebd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

