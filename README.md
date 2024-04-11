# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
 Import the numpy module to use the built-in functions for calculations.
### Step 2: 
 Prepare the lists from each equations and assign in np.array()
### Step 3: 
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
 end the program

## Program:
```python
Program to find the eigen values and eigen vectors.
Developed by: MOHAN.S
RegisterNumber: 212223240094

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:

![alt text](<Screenshot 2024-04-11 142319.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
