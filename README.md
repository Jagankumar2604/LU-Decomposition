# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program.

2.Import the necessary libraries(numpy,scipy.linalg).

3.Define the matrix using numpy.

4.Use lu(),lu_solve(),lu_factor() to get the solutions.

5.End the program.

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: V Jagan Kumar
RegisterNumber: 212225100018
'''

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: V Jagan Kumar
RegisterNumber: 212225100018
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i)
<img width="1143" height="732" alt="Screenshot 2026-02-12 185848" src="https://github.com/user-attachments/assets/66baa54f-a062-449d-8f03-58906a29b6ba" />
(ii) 
<img width="1185" height="747" alt="Screenshot 2026-02-12 185903" src="https://github.com/user-attachments/assets/c45e7f1f-ff0b-444d-82ef-b81442121a04" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

