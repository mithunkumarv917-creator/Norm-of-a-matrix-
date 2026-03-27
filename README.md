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
```
# Register No:Mithun Kumar V
# Developed By:25012629
# 1-Norm of a Matrix
```
```
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")
```
<img width="1204" height="738" alt="image" src="https://github.com/user-attachments/assets/48ab142c-758a-4788-80da-ac9e6dad626c" />




# 2-Norm of a Matrix
```
import numpy as np

# Type your code here
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")


```

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/574460b8-b57a-4e99-a3f4-dd4925cae8df" />



# Infinity Norm of a Matrix
```
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")
```

<img width="1207" height="706" alt="519067795-c201f907-b418-4254-b08a-6d517ee23886" src="https://github.com/user-attachments/assets/a77b4098-19cf-4a96-b8d2-822dbb17f474" />




## Output:
### 1-Norm of a Matrix
<img width="1203" height="300" alt="519067012-28bcb9d4-d62d-486d-b4d1-1326975aa088" src="https://github.com/user-attachments/assets/927403fd-3307-4e5b-9110-dcb4af7eeea8" />

### 2-Norm of a Matrix

<img width="1207" height="341" alt="519067644-d97396eb-0f99-46cc-abce-f066f053385f" src="https://github.com/user-attachments/assets/9220a683-58c7-4b53-b457-c24edea7c2bf" />

### Infinity Norm of a Matrix
<img width="1202" height="298" alt="519068300-91a339ec-1734-4ee8-ad41-9ed3c356ea7d" src="https://github.com/user-attachments/assets/9ea593b1-aa3c-4c72-b9ff-4bb0f680163a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
