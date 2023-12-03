# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Define the matrix A.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the results in output screen using print() function

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YUVARAJ V
#RegisterNumber: 23013769

import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/YuvarajVB/EIGENVALUES-AND-EIGENVECTORS/assets/151488375/9d795337-207f-4699-976b-4ab88af53e4e)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
