# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Import the numpy module to use the built-in functions for calculation
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: VEERARAGAVAN V
#RegisterNumber:23004739
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(b,c))
```
## Output:
![Screenshot 2023-12-16 233028](https://github.com/veerargavanv27/EIGENVALUES-AND-EIGENVECTORS/assets/138955645/7bad1ffc-544b-41b5-a4c2-65dce7abef67)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
