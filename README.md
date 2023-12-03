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
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

```
## Output:
![image](https://github.com/YuvarajVB/EIGENVALUES-AND-EIGENVECTORS/assets/151488375/0253791f-30ec-4835-9a21-fb768db48784)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
