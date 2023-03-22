# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Get the input matrix from the user

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program

## Program:
```
import numpy as np
a=np.array([[4,2],[2,4]])
value,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vector))
```

## Output:


![image](https://user-images.githubusercontent.com/121932143/226883619-7c834e28-7dfb-4d03-9959-005c358e741d.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
