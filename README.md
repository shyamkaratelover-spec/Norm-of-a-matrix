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
```
# Register No:212225220096
# Developed By:SHYAM M
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5894bbaa-c1fe-4d56-9cfd-114d5215a89d" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/10e46e1e-3651-4624-a489-e010dd0db705" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4c88b765-c3da-49ff-8be2-c6652e5f4feb" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
