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
Python
# Register No: 212224100052
# Developed By: SANTHOSH S
# 1-Norm of a Matrix

```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix
![Exp -7](https://github.com/user-attachments/assets/12ed433d-4f19-4a7b-8962-21703c560d63)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Exp -7 (2)](https://github.com/user-attachments/assets/215b8083-9caf-48bf-b54c-e0f1a8270c1f)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Exp -7 (3)](https://github.com/user-attachments/assets/06c30fef-7413-44f2-942a-b7f0e5c85225)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
