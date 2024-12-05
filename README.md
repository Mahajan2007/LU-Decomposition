# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: mahajanani.R
RegisterNumber: 24003555
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
Lu,piv=lu_factor(A)
x=lu_solve((Lu,piv),b)
print(x)
```

## Output:
![lu decomposition](output1.png)
![lu decomposition](output2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

