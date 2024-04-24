# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import numpy as np.
3. Using eval get the input matrix.
4. Declare the formula for lu decompostion and obtain the result.
5. End the program.


## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: RAKSHITHA J
RegisterNumber: 212223240135

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: RAKSHITHA J
RegisterNumber: 212223240135

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition]()

# To print L and U matrix

![output](<Screenshot 2024-04-24 165900.png>)

# To print X matrix (solution to the equations)

![output](<Screenshot 2024-04-24 165918.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

