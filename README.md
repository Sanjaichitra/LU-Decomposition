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

# Program to find the L and U matrix.
# Developed by: SANJAI S
# RegisterNumber: 212223230185
~~~
import numpy as np
import scipy
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
~~~

(ii) To find the LU Decomposition of a matrix
# Program to find the LU Decomposition of a matrix.
# Developed by:SANJAI S 
# RegisterNumber: 212223230185
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
![Screenshot 2023-12-31 192344](https://github.com/Sanjaichitra/LU-Decomposition/assets/144870518/895547d9-ed00-4f4f-b489-8672deb5e44b)
![Screenshot 2023-12-31 192407](https://github.com/Sanjaichitra/LU-Decomposition/assets/144870518/1a213104-ade5-44c3-8870-3e8d2f2e35b6)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

