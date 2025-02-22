# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L U martix using lu().
5. print L and U matrix.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
np.array
A = eval(input())
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = eval(input())
B = eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![lu decomposition](output1.png)
![lu decomposition](output2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

