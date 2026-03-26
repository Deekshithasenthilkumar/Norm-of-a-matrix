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
# Register No:212225100007
# Developed By:DEEKSHITHA S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
A= np.array(matrix)
norm_1=np.linalg.norm(A,1)
print(f"{norm_1:2f}")


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: DEEKSHITHA S
RegisterNumber: 212225100007/25014669
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))



```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (118)" src="https://github.com/user-attachments/assets/ee626c14-0c70-4b04-b93e-afacde0adc7d" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot (119)" src="https://github.com/user-attachments/assets/6d9432ac-205a-4388-a484-330c260112c8" />


### Infinity Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (120)" src="https://github.com/user-attachments/assets/879ceec1-d3b0-4493-bdb5-283fe550b8f0" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
