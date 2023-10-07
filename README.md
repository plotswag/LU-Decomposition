# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.
import numpy library using importstatement 

2.from scipy package importlu()
3.
get input from user and pass it as an array
4.
print L and U matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:jeevanesh 
RegisterNumber:23013802 
# to print l and u matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:jevanesh 
RegisterNumber: 23013802
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
## Output:
![image](https://github.com/plotswag/LU-Decomposition/assets/145822344/aacf8940-9210-4490-9259-dfc1b194dccb)
![image](https://github.com/plotswag/LU-Decomposition/assets/145822344/3357a29d-43d8-4f5a-83c6-0d5a6f79ac93)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

