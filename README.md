# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common error in Java programming: the `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains code that attempts to access an array element beyond its valid index range. The `BugSolution.java` file provides the corrected code.

**Problem:**
The Java code iterates through an array using a for loop, but the loop condition incorrectly allows the loop to try and access one past the end of the array, causing an `ArrayIndexOutOfBoundsException`.

**Solution:**
The solution corrects the loop condition to avoid the out-of-bounds access.

**How to run:**
1.  Clone this repository.
2. Compile and run `Bug.java` to see the exception.
3. Compile and run `BugSolution.java` to see the corrected output.