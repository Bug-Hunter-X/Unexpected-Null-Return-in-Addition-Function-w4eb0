# Unexpected Null Return in Addition Function

This repository demonstrates a common, yet subtle, bug in JavaScript related to null value handling within a simple addition function.  The `foo` function is intended to add two numbers. However, it prematurely returns `null` if either of the input parameters is `null`, even if the other is a valid number. This behavior might not be what's expected in all scenarios and could lead to unexpected results or errors in larger applications.

The `bug.js` file contains the buggy code. The `bugSolution.js` file shows a corrected version that addresses the issue. This example highlights the importance of careful null checks and potentially using alternative strategies for handling null values in mathematical operations.