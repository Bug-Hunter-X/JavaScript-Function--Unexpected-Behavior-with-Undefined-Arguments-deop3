# JavaScript Function: Unexpected Behavior with Undefined Arguments

This repository demonstrates a common JavaScript error: insufficient handling of undefined function arguments.

The `bug.js` file contains a function that correctly handles `null` values, but fails when passed `undefined` arguments.  The `bugSolution.js` provides a corrected version.

## Bug Description:
The function `foo` in `bug.js` does not properly handle cases where one or both of the input arguments are undefined. This results in unexpected behavior or runtime errors.

## Solution:
The solution in `bugSolution.js` adds explicit checks for `undefined` values, ensuring that the function behaves consistently across all possible argument types.