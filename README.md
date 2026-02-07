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
# Register No:5212225230115
# Developed By:JAYENDHIRAN A
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat =np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))  
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans) 
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br><img width="881" height="840" alt="Screenshot 2026-02-07 084954" src="https://github.com/user-attachments/assets/3872a369-20a3-4cfc-9f3b-9e7d45471a16" />
### 2-Norm of a Matrix
<br><img width="761" height="862" alt="Screenshot 2026-02-07 085017" src="https://github.com/user-attachments/assets/9adaeb0a-9c9f-42c2-bfe8-6dc223a8c4da" />
### Infinity Norm of a Matrix
<br><img width="765" height="847" alt="Screenshot 2026-02-07 085028" src="https://github.com/user-attachments/assets/6eda1545-a9f7-4b4c-a78a-dd8ae0ccce67" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
