# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Factorize matrix 𝐴 into 𝐿 𝑈 form (with pivoting if needed).
Solve 𝐿 𝑦=𝑏 using forward substitution.
Solve 𝑈 𝑥= 𝑦 using backward substitution.
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Mahith M 
RegisterNumber:212225040121

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
(ii) To find the LU Decomposition of a matrix
```

## Output:
<img width="1918" height="913" alt="Screenshot 2026-05-20 141020" src="https://github.com/user-attachments/assets/f45d6e7c-6205-4edc-8708-935ee378e68d" />

<img width="1875" height="857" alt="Screenshot 2026-05-20 140158" src="https://github.com/user-attachments/assets/5ed5bf26-9d13-473a-85f3-251011fd3384" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

```

## Output:



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

