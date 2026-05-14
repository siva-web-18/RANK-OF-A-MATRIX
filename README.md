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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)

## Output:
<img width="1270" height="778" alt="Screenshot 2026-05-14 205115" src="https://github.com/user-attachments/assets/2c5e9744-12a0-48cd-9058-763ffbf6ece8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

