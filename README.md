# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 6 Assignment

#### Assigned: November 16, 2026

#### Due: November 25, 2026 (before 9:30 AM)

---

#### Learning Goals

1.  Vectorize function,
1.  Create arrays using Numpy, and
1.  Generate a graph using Matplotlib.

#### Description

This lab will utilize the user-defined for the CDF of the logistic distribution created in Laboratory 5 to cover vectorizing functions, creating arrays using Numpy and generating a figure created with Matplotlib. The Python code contained in your starter repository is provide at the bottom of this assignment.

#### Step 1

Edit the first cell (markdown), to update your personal information for Lab Seven.

#### Step 2

In cell two below the comment for step 2, enter the user-defined function created in Lab Five that calculates the CDF of the logistic distribution. The function should accept three inputs: x, mu and sigma.


#### Step 3

In cell two below the step 3 comment line, create the a vectorized version of the user-defined function created for Step 2. Vectorized functions were presented in Day 13 Lecture of the class notes.


#### Step 4

In cell two below the comment for step 3, create an array named x using the Numpy linspace function that creates an array containing 500 points from -10 to +10.

#### Step 5

In cell two below the step 5 comment line, create the array containing values for the CDF of the logistics distribution with parameters: mu=2.0, and sigma=5.0 using the values of stored in x (created in Step 4) using the vectorized function created in Step 3.

#### Step 6

Step should not require any modifications of your code to produce a graph based upon Steps 2-7 above.

#### Step 7 

After running and testing your program, save the Jupyter Notebook. Upload your repository using GitHub desktop.

---

```python
import math
import numpy as np
import matplotlib.pyplot as plt

# Step 2 - insert the user-defined function from Lab Six that calculates the CDF of the logistic distribution below this line


# Step 3 - Insert the Python command(s) to vectorize your user-defined function from Step 1


# Step 4 - create array containing 500 points (using the linspace Numpy command) for values of x from -10 to +10

x=

# Step 5 - create the array y using the vectorized CDF for the logistic distribution with mu=2.0 and sigma=5.0 created in Step 2

y=

# Step 6 - using the code below to create a graph of the data created in Steps 3 and 4

plt.plot(x,y,'b')
plt.show()
```