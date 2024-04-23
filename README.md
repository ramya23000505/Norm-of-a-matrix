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

'''
Program to find 2-norm of a matrix.

Developed by: RAMYA R

RegisterNumber: 212223230169
'''

### 1-Norm of a Matrix

```
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```

### 2-Norm of a Matrix

```
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```

### Infinity Norm of a Matrix

```
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))
```

## Output:

### 1-Norm of a Matrix

![Screenshot 2024-04-23 113012](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/46b5f7e6-fa3e-4356-8aca-aa3c8deca92f)

![Screenshot 2024-04-23 113016](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/0e383531-8620-40d6-a862-51fb7d4d50ad)


### 2-Norm of a Matrix

![Screenshot 2024-04-23 113026](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/b615db05-87fd-4154-81a0-4c36120d8650)

![Screenshot 2024-04-23 113033](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/7cc11fd1-42b5-47aa-a3f5-4c9a18cbcf0e)


### Infinity Norm of a Matrix

![Screenshot 2024-04-23 113042](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/697f4b03-62b4-4207-b454-6006cda50441)

![Screenshot 2024-04-23 113048](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/8da29788-9637-4010-9b9e-ddf8b158a166)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
