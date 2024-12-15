# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The `bug.java` file contains code that produces an `ArrayIndexOutOfBoundsException`.  The `bugSolution.java` file provides the corrected code.

The error occurs because the loop condition `i <= arr.length` should be `i < arr.length` to avoid accessing an index beyond the array's bounds.  Array indices in Java are zero-based, meaning they range from 0 to length-1.