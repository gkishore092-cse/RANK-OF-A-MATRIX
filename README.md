# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import os and numpy
### Step 2: creating array "a" which consist of a matrix
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: printing the rank of the matrix
## Program:
```
DEVELOPED BY : KISHORE G
REGISTER NUMBER : 212225040191

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)

```

## Output:
<img width="752" height="637" alt="image" src="https://github.com/user-attachments/assets/79c7bb2f-7309-40f2-a5d1-029e18a1fe56" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

