# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# Step 1
Import the numpy module to use the built-in functions for calculation.
# Step 2
Prepare the lists from each linear equations and assign in np.array(). 
# Step 3
Using the scipy.linalg and imort lu_fator and lu_solve we get the values.
# Step 4
End the program
 

## Program:
(i) To find the L and U matrix
 # Program to find L and U matrix using LU decomposition.
 # Developed by: SANJAI S 
 # RegisterNumber: 23013614
```
import numpy as np
import scipy
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
 # Program to solve a matrix using LU decomposition.
 # Developed by: SANJAI S 
 # RegisterNumber: 23013614
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2023-12-31 192344](https://github.com/AkilaMohan/LU-Decomposition/assets/144870518/14068ff6-2995-440b-ab69-7450415b5e0c)
![Screenshot 2023-12-31 192407](https://github.com/AkilaMohan/LU-Decomposition/assets/144870518/e1f9c2c6-9008-4484-a79d-080ec4269de9)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

