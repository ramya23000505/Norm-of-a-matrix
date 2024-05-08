# Norm of a matrix
# Date:
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
```
Program to find 2-norm of a matrix.
Developed by: RAMYA R
RegisterNumber: 212223230169
```
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
![alt text](<7 a in.png>)
![alt text](<7 a ot.png>)

### 2-Norm of a Matrix
![alt text](<7 b in.png>)
![alt text](<7 b ot.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2024-05-08 191447.png>)
![alt text](<Screenshot 2024-05-08 191501.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
