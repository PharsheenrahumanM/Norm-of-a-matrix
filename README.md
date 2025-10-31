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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix


'''
Program to find 2-norm of a matrix.
Developed by: yourname: Pharsheen Rahuman M
RegisterNumber: 212224230193
'''
import numpy as np

# Type your code here
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
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/19b0ddb1-1522-4098-89d8-61f46c90fd65" />


### 2-Norm of a Matrix
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/ebe36483-fa93-4770-be0a-f035bdfeb43b" />


### Infinity Norm of a Matrix
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/1ae0d15e-75a4-4dc5-bfa4-39a249052300" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
