# LU Decomposition without zero on the diagonal

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
~~~ python
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ragul.vk
RegisterNumber: 21003061
*/

import numpy as np
import scipy
from  scipy.linalg import lu
a = eval(input())
P,L,U=lu(a)
print(L)
print(U)
~~~
~~~ python
'''Program to solve a matrix using LU decomposition.
Developed by: Ragul.vk
RegisterNumber: 21003061
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = eval(input())
b = eval(input())
lu,piv= lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)
~~~


## Output:
![lu decomposition](lu.png)
![](ludecomposition.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

