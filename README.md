# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
<h3> 1-norm </h3>

Step 1: Start the program.

Step 2: Read the input matrix using np.array().

Step 3: Calculate the 1-norm using np.linalg.norm(matrix, 1).

Step 4: Format the result to two decimal places.

Step 5: Print the 1-norm and stop the program.

<h3> 2-norm </h3>

Step 1: Start the program.

Step 2: Read the input matrix using np.array().

Step 3: Calculate the 2-norm using np.linalg.norm(matrix, 2).

Step 4: Format the result to two decimal places.

Step 5: Print the 2-norm and stop the program.

<h3>  Infinity norm </h3>

Step 1: Start the program.

Step 2: Read the input matrix using np.array().

Step 3: Calculate the infinity norm using np.linalg.norm(matrix, np.inf).

Step 4: Format the result to two decimal places.

Step 5: Print the infinity norm and stop the program.
## Program:
```Python
# Register No:212225240004
# Developed By:ADITYA JORIM F S
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
<img width="969" height="474" alt="Screenshot 2026-03-20 160430" src="https://github.com/user-attachments/assets/cbec4153-52f5-4404-8d1c-3621e8502d4f" />


### 2-Norm of a Matrix
<img width="993" height="472" alt="Screenshot 2026-03-20 160609" src="https://github.com/user-attachments/assets/07c993ab-9b1b-4e36-92ef-e9bae5e14507" />


### Infinity Norm of a Matrix
<img width="976" height="462" alt="Screenshot 2026-03-20 160706" src="https://github.com/user-attachments/assets/66a2c36c-3906-4cde-90cb-2cff17b53e9e" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
