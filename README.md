# JavaScript Bug: TypeError when accessing property of undefined value

This repository demonstrates a common JavaScript error and its solution. The bug arises when attempting to access a property of an undefined variable, which results in a `TypeError`.  The solution involves adding a check for the undefined value before accessing the property.

## Bug

The `bug.js` file contains a function that calculates the length of an array. However, it does not handle the case where the input is `undefined`, leading to a `TypeError`. 

## Solution

The `bugSolution.js` file provides a corrected version of the function.  It checks for `undefined` before accessing the `length` property, preventing the error. This approach enhances the robustness and reliability of the code.