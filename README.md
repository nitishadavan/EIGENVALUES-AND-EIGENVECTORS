# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by: D.Nitish Adavan
#RegisterNumber:212224240107
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
~~~
## Output:

<img width="1285" height="931" alt="image" src="https://github.com/user-attachments/assets/b668d939-b3a6-47a1-8d12-cbaa16f3b8a4" />
<img width="1283" height="272" alt="image" src="https://github.com/user-attachments/assets/4dd2afdd-8e8e-4237-b550-54f8d6006b59" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
