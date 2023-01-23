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
# Register No:SATHISH R
# Developed By:22009045
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![program 1](https://user-images.githubusercontent.com/120574768/214040517-b929e539-53ca-4c46-ac84-1f7795f602e0.png)



### 2-Norm of a Matrix

![program 2](https://user-images.githubusercontent.com/120574768/214040527-de44bc71-4aa7-4dce-a016-5b74606dddf2.png)


### Infinity Norm of a Matrix

![program 3](https://user-images.githubusercontent.com/120574768/214040541-604ceb5e-c66b-4391-b626-4cb4ef820687.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
