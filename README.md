# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the listfrom each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Naveen kumar
#RegisterNumber: 23000827

import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Eigen values](https://github.com/Naveenkumarvedarajan/EIGENVALUES-AND-EIGENVECTORS/assets/147140428/53e6d422-ae8c-455d-829a-713badaffd77)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
