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
# Register No: 22005234
# Developed By: hanumanth
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: hanumanth 
RegisterNumber:22005234
'''
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))




# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix

![Screenshot (13)](https://user-images.githubusercontent.com/121033192/214382312-539a7d9c-5557-4cb7-b23c-346400d99850.png)

### 2-Norm of a Matrix
![Screenshot (14)](https://user-images.githubusercontent.com/121033192/214382602-47113dec-9bd7-495b-8250-b62a3e6084fb.png)


### Infinity Norm of a Matrix
![Screenshot (15)](https://user-images.githubusercontent.com/121033192/214382768-2afa1595-1178-433e-b03b-51cc7659c484.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
