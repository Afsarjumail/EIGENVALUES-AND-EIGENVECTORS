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
Get the input matrix from the user

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: S Afsar jumail
#RegisterNumber: 212222240004
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![2023-05-29 (6)](https://github.com/Afsarjumail/EIGENVALUES-AND-EIGENVECTORS/assets/118343395/36f85771-eeb3-453a-851c-d815c6236ae0)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
