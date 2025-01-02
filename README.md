# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript related to the handling of null values. The `bug.js` file contains a function that returns `null` if either of its input arguments is `null`. This can lead to unexpected behavior in applications that might not anticipate `null` values being returned. The `bugSolution.js` file provides a solution showing how to handle these scenarios more effectively.

## How to reproduce the bug:
1. Clone the repository.
2. Run `bug.js`. Observe that calling the `foo` function with a null input returns `null`.