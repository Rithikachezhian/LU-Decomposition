# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built_in function for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.solve(we ca find the solutions)
4. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RITHIKA N
RegisterNumber: 23013374
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RITHIKA N
RegisterNumber: 23013374
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![Screenshot 2023-12-16 011122](https://github.com/Rithikachezhian/LU-Decomposition/assets/145742406/bdb9c826-1ec7-4bd9-8ea3-d7f93828e68a)
![Screenshot 2023-12-16 011141](https://github.com/Rithikachezhian/LU-Decomposition/assets/145742406/60ff5f79-1300-447c-ba34-cac76f12d38f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

