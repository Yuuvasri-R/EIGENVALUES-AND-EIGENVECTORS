# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: Yuuvasri R

#RegisterNumber:212225230313

import numpy as np

A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
<img width="883" height="238" alt="Screenshot 2026-02-05 140103" src="https://github.com/user-attachments/assets/8746623c-f8cd-4ae8-8ce8-eeeccccaa963" />
<img width="883" height="259" alt="Screenshot 2026-02-05 140125" src="https://github.com/user-attachments/assets/81ca0d04-e91d-425d-9b66-05445730357c" />

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program






