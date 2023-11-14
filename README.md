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

# Register No:23000800
# Developed By:KISHORE KUMAR U
# 1-Norm of a Matrix
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inver=np.linalg.inv(A)
print(inver)




# 2-Norm of a Matrix
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)





# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)





```
## Output:

![image](https://github.com/Kishorekumar22060/Norm-of-a-matrix/assets/141472136/0a0c2183-7904-4d18-82a2-bc14562b7aa5)

![image](https://github.com/Kishorekumar22060/Norm-of-a-matrix/assets/141472136/6a78698e-8b3d-4589-8caf-e68786e7b0f9)

![image](https://github.com/Kishorekumar22060/Norm-of-a-matrix/assets/141472136/536de0a6-3416-4322-8049-9dd3c8b78886)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
