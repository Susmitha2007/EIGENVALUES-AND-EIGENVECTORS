# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module as np.array
### Step 2: 
Define the matrix as "a" using np.array([],[],[])
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Displaying the eigenvalues and eigenvectors using print function
## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by:Nara Guna Susmitha 
#RegisterNumber:24010204
import numpy as np
matrix=np.array([[4,2],[2,4]])
e_value,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_value,e_vectors))

```

## Output:
![output](<Screenshot 2024-11-18 210137-1.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
