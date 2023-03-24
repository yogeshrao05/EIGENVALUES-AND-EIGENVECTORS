# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
we have imported numpy which is needed.

Step 2:
we have created a matrix using np.array with different values in it.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
finally,print the values of the eigen values and eigen vectors.

## Program:
```
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
value,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vector))

## Output:
```
![image](https://user-images.githubusercontent.com/122008288/227437288-5d557ee7-86e0-4631-8bfa-b73f4cf7fb2a.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
