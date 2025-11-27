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
# Register No:25013390
# Developed By:HARISH K
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(f"{norm2:.2f}")


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")



```
## Output:
### 1-Norm of a Matrix
 <img width="1914" height="1090" alt="Screenshot 2025-11-27 213717" src="https://github.com/user-attachments/assets/4476957d-b290-4be3-8eaa-61d64f564101" />


### 2-Norm of a Matrix
 <img width="1917" height="1089" alt="Screenshot 2025-11-27 213732" src="https://github.com/user-attachments/assets/0758c7d1-4e87-4883-bc6a-f637e4640211" />


### Infinity Norm of a Matrix
 <img width="1919" height="1089" alt="Screenshot 2025-11-27 213745" src="https://github.com/user-attachments/assets/6950ba33-2d8a-4ec4-b62f-f467d5a22114" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
