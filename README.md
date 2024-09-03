## DATE:
## EX 4 - EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```


#Program to find the eigen values and eigen vectors.
#Developed by: AMALJOSH MAADHAV J
#RegisterNumber: 212223230012



import numpy as np
A = np.array([[4,2],[2,4]])
B,C = np.linalg.eig(A)
print(f"Eigen values are {B} and Eigen Vectors are {C}")





```
## Output:
![image](https://github.com/user-attachments/assets/fe6dfd5a-d443-41fe-916b-d8caedc9565f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
