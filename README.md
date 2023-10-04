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
```
#Program to find the eigen values and eigen vectors.
#Developed by: Richardson A
#RegisterNumber: 23000803

import numpy as np
A=np.array([[4,2],[2,4]])
values,vactors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vactors))
```

## Output:

![image](https://github.com/Richard01072002/EIGENVALUES-AND-EIGENVECTORS/assets/141472248/b2a57643-07ff-47d5-a146-e434c36b0df9)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
