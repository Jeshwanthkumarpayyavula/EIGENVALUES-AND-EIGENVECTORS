# EIGENVALUES-AND-EIGENVECTORS
# Name:Jeshwanth Kumar
# Reg.No:212223240114
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
#Developed by: Jeshwanth kumar
#RegisterNumber: 23002519
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Jeshwanthkumarpayyavula/EIGENVALUES-AND-EIGENVECTORS/assets/145742402/764bfc95-6577-4178-b3bd-994a2a91a722)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
