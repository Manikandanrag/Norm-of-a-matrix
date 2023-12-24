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
## PROGRAM:
```
# Register No: 23004754
# Developed By: Manikandan R
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![214384785-047264e7-6f2d-40f8-ace3-b34c5c982608](https://github.com/Manikandanrag/Norm-of-a-matrix/assets/138849491/7fa4be3a-4c34-461d-83ba-b762dee356ba)


### 2-Norm of a Matrix
![image](https://github.com/Manikandanrag/Norm-of-a-matrix/assets/138849491/9765a04f-70eb-4de8-b067-3ea144ab00c4)


### Infinity Norm of a Matrix
![image](https://github.com/Manikandanrag/Norm-of-a-matrix/assets/138849491/163f9bb9-7350-4ebf-8f5a-d0f5b6877c05)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
