# Off-by-One Error in Java While Loop

This repository demonstrates a common off-by-one error in a Java while loop. The code intends to print numbers from 1 to 10, but due to the placement of the post-increment operator, it actually prints numbers from 1 to 11.  The solution demonstrates the correct way to handle the loop condition to avoid the error.

## Bug
The `Bug.java` file contains the erroneous code.  The loop terminates one iteration later than expected, resulting in an unexpected output. 

## Solution
The `BugSolution.java` file provides the corrected code. The solution modifies the loop condition to accurately control the number of iterations.