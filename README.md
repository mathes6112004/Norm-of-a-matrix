# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
### 1-Norm of a Matrix
```
python program to find the 1-Norm of a matrix
Developed by:MATHESWARAN.K
Reference No:212222110024
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
### 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: MATHESWARAN K
RegisterNumber: 212222110024
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
### Infinity Norm of a Matrix
```
program to find the Infinity of a matrix and display the result in two decimal places.
Name:MATHESWARAN K
Register No:212222110024
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![p2](https://user-images.githubusercontent.com/119477782/237012755-8885bf42-4afd-46b8-806a-b4fb88a296d8.png)


### 2-Norm of a Matrix
![p21](https://user-images.githubusercontent.com/119477782/237012788-1d7a9ca4-5d37-4e18-9010-4b41df24f548.png)


### Infinity Norm of a Matrix

![p211](https://user-images.githubusercontent.com/119477782/237012825-320d9ab5-81cb-445d-a7a1-23fb30105b2f.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
