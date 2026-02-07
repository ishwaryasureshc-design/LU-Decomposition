# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1.Start the program

2.Import the necessary libraries(numpy,scipy.linalg)

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ishwarya.s
RegisterNumber: 212225240053
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ishwarya.s
RegisterNumber: 212225240053
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)


```

## Output:
<img width="1366" height="768" alt="Screenshot 2026-02-07 092332" src="https://github.com/user-attachments/assets/9e2dbb8b-a5c0-4f8f-805a-74e5bccb77c2" />

<img width="1366" height="768" alt="Screenshot 2026-02-07 092347" src="https://github.com/user-attachments/assets/c1789f43-f383-4e9b-b0a8-4e9d1d1e3617" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

