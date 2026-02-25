# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Input the square matrix A of order n X n.

2.Initialize lower triangular matrix L as identity matrix and upper triangular matrix U as zero matrix.

3. Compute the elements of U row-wise and Į column-wise using elimination method such that A = LU

4. Display the matrices L and U.

## Program:
(i) To find the L and U matrix
```python

Program to find the L and U matrix.
Developed by: Ajithkumar .J
RegisterNumber: 212225040015

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


```
(ii) To find the LU Decomposition of a matrix
```python


Program to find the LU Decomposition of a matrix.
Developed by: Ajithkumar .J
RegisterNumber: 212225040015
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))

lu,piv=lu_factor(A)
X=lu_solve((lu , piv),b)
print(X)

```

## Output:
![lu decomposition]()
<img width="995" height="871" alt="{5892861A-3BA5-4376-AF6B-1ADC5B22C5F3}" src="https://github.com/user-attachments/assets/44e88f7d-614d-4460-b002-31fdadc602cf" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/90665dca-0b23-4983-803f-030ea34aa859" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

