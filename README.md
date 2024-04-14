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
# Register No: 212223230169
# Developed By: RAMYA R

# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix

import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-14 191815](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/e5468448-4237-4e40-87cd-a42761097725)
![Screenshot 2024-04-14 191823](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/465ca763-7bba-4825-a331-444d3a189a2c)

### 2-Norm of a Matrix
![Screenshot 2024-04-14 191830](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/f3a0ea37-bf96-447c-a58c-a5afe03939f6)
![Screenshot 2024-04-14 191837](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/30078e08-bb7e-4831-b73c-9aacf680fcc8)

### Infinity Norm of a Matrix
![Screenshot 2024-04-14 191843](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/1d2d856d-d306-405d-a3f7-a49f8d14d21a)
![Screenshot 2024-04-14 191850](https://github.com/ramya23000505/Norm-of-a-matrix/assets/149370791/66365532-b567-4450-a8c6-71ba6ac5ba77)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
