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
# Register No:212224230257
# Developed By:SAVISH R
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SAVISH R
RegisterNumber: 212224230257
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/d6456d2a-a7f0-46db-883c-f9adde03fff3)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/d648b5e9-9553-4db2-a208-2e95e2b678d0)

<br>
<br>

### Infinity Norm of a Matrix
<br>![image](https://github.com/user-attachments/assets/ee020fd5-7709-4bc4-8a25-b7e7a29086f0)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
