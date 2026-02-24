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
# Register No: 212225240045
# Developed By: HARIHARAN M
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_mat="{:.2f}".format(ans)
print(Norm_mat)




# 2-Norm of a Matrix

'
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_mat="{:.2f}".format(ans)
print(Norm_mat)





# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print(ans)





```
## Output:
### 1-Norm of a Matrix

![WhatsApp Image 2026-02-24 at 1 57 14 PM](https://github.com/user-attachments/assets/17b2cf20-45fc-4eca-b0a5-61764a45a272)


### 2-Norm of a Matrix

![WhatsApp Image 2026-02-24 at 1 57 58 PM](https://github.com/user-attachments/assets/3c537dbe-4a64-438d-99f3-c859ef1a63a6)


### Infinity Norm of a Matrix

![WhatsApp Image 2026-02-24 at 1 58 41 PM](https://github.com/user-attachments/assets/92d37951-760b-4bbe-a4de-be60f29597d3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
