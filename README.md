![image](https://github.com/MohanKumar755/EIGENVALUES-AND-EIGENVECTORS/assets/146155007/2fc136e4-308f-4cf2-a518-c82ec319ebe6)# EIGENVALUES-AND-EIGENVECTORS
# DATE: 06/04/2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
import numpy as np
A=np.array([[2,2],[1,3]])
E,EV=np.linalg.eig(A)
print("Eigen values are\n",E,"\nEigen vectors are:\n",EV)
```
## Output:
![rank of matrix](https://github.com/MohanKumar755/EIGENVALUES-AND-EIGENVECTORS/assets/146155007/d19f2a84-3931-40f8-a84b-147858686e4d)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
