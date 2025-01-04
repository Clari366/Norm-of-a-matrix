# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm1:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Algorithm2:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Algorithm3:
	1. Get the input matrix using np.array()   
    2. Find the Infinity-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
# Register No: 24009830
# Developed By: Clarissa K
## 1-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```





##2_norm of matrix


```import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)
```

## Infinity Norm of a Matrix


```import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)
```

## Output:

### 1-Norm of a Matrix
![Alt text](<Screenshot from 2025-01-04 21-03-29.png>)
### 2-Norm of a Matrix
![Alt text](<Screenshot from 2025-01-04 21-02-06.png>)



### Infinity Norm of a Matrix
![Alt text](<Screenshot from 2025-01-04 21-04-00.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
