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
```Python
# Developed By:PYNAM VINODH
# Register No:212223240131
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/PYNAMVINODH/Norm-of-a-matrix/assets/145742678/a20b9e24-d42e-42c3-9336-2c084b80eec6)



### 2-Norm of a Matrix
![image](https://github.com/PYNAMVINODH/Norm-of-a-matrix/assets/145742678/0eb82b2e-a2d7-4e9d-9d41-49a09f1ac318)


### Infinity Norm of a Matrix
![image](https://github.com/PYNAMVINODH/Norm-of-a-matrix/assets/145742678/8f4cd3fe-5674-44e2-9895-573df9f78086)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
