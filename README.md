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
# Register No:23003133
# Developed By:MOHAMED RIDWAN A
# 1-Norm of a Matrix
```
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
c='{:.2f}'.format(b)
print(c)
```


# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: MOHAMED RIDWAN A
RegisterNumber:23003133 
```
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
c='{:.2f}'.format(b)
print(c)
```




# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: MOHAMED RIDWAN A
RegisterNumber: 23003133
'''
```
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
c='{:.2f}'.format(b)
print(c)
```



## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="518" alt="image" src="https://github.com/MOHAMEDRIDWAN/Norm-of-a-matrix/assets/146993368/97085199-af50-495f-afcf-e4262b1dae9b">

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="520" alt="image" src="https://github.com/MOHAMEDRIDWAN/Norm-of-a-matrix/assets/146993368/9fec4bfd-1f03-4cdb-99f2-10fa66e0b816">

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="515" alt="image" src="https://github.com/MOHAMEDRIDWAN/Norm-of-a-matrix/assets/146993368/e3c0e1ea-ee6f-438c-b85b-42b93290c041">




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
