# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module to use built-in linear algebra functions.
### Step 2: Create the matrix using np.array() and store it in a variable A.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors to display the result.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rakisha R
#RegisterNumber:212225230223
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[2,2],[1,3]])
eig_value,eig_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```
## Output:
<img width="1243" height="728" alt="image" src="https://github.com/user-attachments/assets/5409a200-2255-4516-8020-261e4d153890" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
