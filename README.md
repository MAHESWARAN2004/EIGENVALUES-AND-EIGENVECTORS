# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
start a program.
### Step 2: 
import a numpy as py.
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print a eigen value and vectors.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MAHESWARAN K
#RegisterNumber: 212222110023

import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```
## Output:
![M4p](https://user-images.githubusercontent.com/119478181/226254098-ceaba199-df5f-4389-8c83-2508522e6b46.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
