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
# Register No:22005703
# Developed By:Mithra mukundaa S G
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat= np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix!
![Screenshot_20230126_081431](https://user-images.githubusercontent.com/121608770/214866360-b0e79cdc-fe21-40ac-b438-4b247fb915b6.png)


### 2-Norm of a Matrix
![Screenshot_20230126_081442](https://user-images.githubusercontent.com/121608770/214865853-913ecce9-63c3-4a36-baa4-84d7373d19e4.png)


### Infinity Norm of a Matrix
![Screenshot_20230126_081451](https://user-images.githubusercontent.com/121608770/214866020-81bbcaa4-1de9-45ff-9176-21152b3faae3.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
