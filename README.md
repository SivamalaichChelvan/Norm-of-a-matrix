# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
`
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:

## 1-Norm of a Matrix
```
import numpy as np
A =  np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)
```


## 2-Norm of a Matrix
```
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
print(f"{norm1:.2f}")

```


## Infinity Norm of a Matrix
```
import numpy as np
A=np.array(eval(input()))
result=np.linalg.norm(A,np.inf)
print(f"{result:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="887" alt="Screenshot 2026-05-24 160652" src="https://github.com/user-attachments/assets/8df12d57-0539-47de-910c-6b72d8e7cc1a" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-05-24 160710" src="https://github.com/user-attachments/assets/63622cba-2825-4986-a55d-64b521293fca" />


### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-05-24 160735" src="https://github.com/user-attachments/assets/d56b4c84-3957-429b-a09f-0748c2f15916" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
