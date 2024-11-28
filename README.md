![image](https://github.com/user-attachments/assets/c526f25f-718d-4719-b1f0-59a601a3bc04)# EIGENVALUES-AND-EIGENVECTORS
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
import numpy as np
a= np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## output:
![Screenshot 2024-11-28 101929](https://github.com/user-attachments/assets/6aa1927f-8b5c-491f-956a-f2484daea57b)

  
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
