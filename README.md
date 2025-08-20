# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

Import the numpy module to use the built-in functions for calculation

### Step 2:

Prepare the lists from the matrix and assign in np.array()

### Step 3:

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

End the Program

## Program:
```
# Program to find the eigen values and eigen vectors
# Developed by:
# RegisterNumber:

import numpy as np

# Define the matrix
A = np.array([[2, 2],
              [1, 3]])

# Find eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(A)

# Display results in required format
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```

## Output:
<img width="1895" height="1029" alt="Screenshot 2025-08-20 083356" src="https://github.com/user-attachments/assets/4e60308f-306b-4921-9e71-6c3843863740" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
