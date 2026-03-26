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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:2f}".format(ans)
print(norm)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: VIGNESH V
RegisterNumber: 212225230298
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
a="{:.2f}".format(ans)
print(a)



```
## Output:
### 1-Norm of a Matrix

<img width="1306" height="280" alt="image" src="https://github.com/user-attachments/assets/cca3e17c-de10-452a-b9d1-2cfe088f0a1c" />


### 2-Norm of a Matrix


<img width="1323" height="265" alt="image" src="https://github.com/user-attachments/assets/6370009c-6ed5-4090-ae28-be069425dd67" />


### Infinity Norm of a Matrix

<img width="1337" height="240" alt="image" src="https://github.com/user-attachments/assets/7cdb4184-0a9a-44dd-88a0-2951d763a2db" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
