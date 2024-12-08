# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X

## Program:
(i) To find the L and U matrix
```
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

p,l,u=lu(A)

print(l)

print(u)
/*
Program to find the L and U matrix.
Developed by: Saiprasath.P
RegisterNumber: 24900076
*/

(ii) To find the LU Decomposition of a matrix

import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

b=np.array(eval(input()))

Lu,piv=lu_factor(A)

s=lu_solve((Lu,piv),b)

print(s)
/*
Program to find the LU Decomposition of a matrix.
Developed by: Saiprasath.P
RegisterNumber: 24900076
*/


## Input:
import numpy as np

from scipy.linalg import lu

A=np.array(eval(input()))

p,l,u=lu(A)

print(l)

print(u)


## Output:
![image](https://github.com/user-attachments/assets/f1d72d41-e3de-4deb-aeec-017bde3aec5e)

![image](https://github.com/user-attachments/assets/481a3cdf-8da1-48d2-8d6c-6e3e69511458)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

