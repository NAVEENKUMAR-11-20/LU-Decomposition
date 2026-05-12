# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1: Start the program.
### Step 2: Import the required libraries numpy and scipy.linalg.
### Step 3: Read the elements of the matrix from the user and store them in a matrix form.
### Step 4: Use the lu() function from scipy.linalg to decompose the matrix into Lower (L) and Upper (U) triangular matrices.
### Step 5: Display the matrices L and U.
### Step 6: Stop the program.

## Program:
(i) To find the L and U matrix
```python
Program to find L and U matrix using LU decomposition.
Developed by: NAVEEN KUMAR P
RegisterNumber: 212224240102

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by: NAVEEN KUMAR P
RegisterNumber: 212224240102

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
l,p=lu_factor(A)
x=lu_solve((l,p),B)
print(x)
```

## Output:

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/46e9b9ce-a53c-493b-928b-1586de37a588" />


<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/e17e4756-9c4f-43b7-904d-aa1eb494a9b3" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

