# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Form the matrix
Take the given square matrix A.
### Step 2: Find Eigenvalues
Compute the characteristic equation
det(A−λI)=0
and solve it to get the eigenvalues  λ.

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Find Eigenvectors
For each eigenvalue 
𝜆
λ, substitute into
(A−λI)X=0

and solve to get the eigenvector(s) 

X.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: GOPINATH S
#RegisterNumber:25012981
import numpy as np
a=[[4,2],[2,4]]
b=np.array(a)
value,vectors=np.linalg.eig(b)
print(f"Eigen values are {value} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1366" height="768" alt="Screenshot 2025-11-21 180413" src="https://github.com/user-attachments/assets/dff10c49-e578-4258-87cd-1a404e697a9f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
