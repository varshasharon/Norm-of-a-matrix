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

# Register No: E. VARSHA SHARON
# Developed By: 22004867
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![1 NORM](https://user-images.githubusercontent.com/98278161/215110756-e3edb349-353f-44f7-9d45-77cab84d1998.png)


### 2-Norm of a Matrix

![2 NORM](https://user-images.githubusercontent.com/98278161/215110837-59689dc3-260b-4295-9ac4-dac8e87f4814.png)


### Infinity Norm of a Matrix

![INF NORM](https://user-images.githubusercontent.com/98278161/215110866-bcde8162-8df1-4af6-96f2-ea3cfc92014f.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
