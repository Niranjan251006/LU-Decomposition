# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## 1.Define the package as scipy.linalg import lu.
## 2.Get input from user and print L and U matrix by 'print'.
## 3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
## 4.print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NIRANJAN S
RegisterNumber: 212224040221
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NIRANJAN S
RegisterNumber: 212224040221
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/472ddd53-a6fc-417b-96b0-48b3b58823e3)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

