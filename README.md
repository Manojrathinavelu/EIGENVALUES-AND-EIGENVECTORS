# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner\

## Algorithm:
### Step1 : import numpy as np
### Step 2: Asign the values for n
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Note the output

## Program:

#Program to find the eigen values and eigen vectors.
#Developed by: Manoj Karthik.R
#RegisterNumber: 22003728

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors,)

## Output:
![eigen](https://user-images.githubusercontent.com/119560395/214597869-d90a3151-586a-4a02-8a6c-44cb54e2c81b.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
