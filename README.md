# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid index range, causing the exception. The `bugSolution.java` file provides a corrected version of the code. 

**Understanding the Bug**

In Java, arrays are zero-indexed. An array of length *n* has valid indices from 0 to *n-1*. Trying to access an index outside this range leads to an `ArrayIndexOutOfBoundsException`.  The original code incorrectly iterates from 0 up to and *including* `arr.length`, leading to an attempt to access `arr[5]` in an array with only indices 0-4.