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
# Register No: 25008769
# Developed By: JAIHARI S
# 1-Norm of a Matrix
import numpy as np
mat=np.array (eval(input()))
ans=np.linalg.norm(mat,1)
a="{:.2f}".format(ans)
print(a)




# 2-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n=f"{a:.2f}"
print(n)




# Infinity Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n=f"{a:.2f}"
print(n)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="1352" height="375" alt="image" src="https://github.com/user-attachments/assets/a57b36dc-1f2f-4f9d-af4f-8be0cd7de754" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="863" height="324" alt="image" src="https://github.com/user-attachments/assets/069fe127-0be0-4b78-b7f9-ffa6f3133bbf" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="775" height="260" alt="image" src="https://github.com/user-attachments/assets/b896101d-eb1d-446a-b4b8-aeee17f844f9" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
