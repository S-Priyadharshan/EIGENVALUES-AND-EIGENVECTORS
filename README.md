# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define the matrix.

### Step 2: Find the eigenvalues and eigenvectors of the matrix using numpy's np.linalg.eig() function.

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: End the program and print the output.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Priyadharshan S
#RegisterNumber:212223240127
import numpy as np 
matrix=[[2,2],[1,3]]
eigenval,eigenvec=np.linalg.eig(matrix);
print("Eigen values are {} and Eigen Vectors are {}".format(eigenval,eigenvec))
```
## Output:

![image](https://github.com/S-Priyadharshan/EIGENVALUES-AND-EIGENVECTORS/assets/145854138/8450176f-990f-4a49-adb8-48b2221965e9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
