# Unexpected Results from Type Coercion in JavaScript Functions

This repository demonstrates a common issue in JavaScript where implicit type coercion can lead to unexpected results, specifically within mathematical functions.

The `bug.js` file contains a simple example showcasing this problem. The `bugSolution.js` file provides a corrected version.

## Problem

The original `subtract` function in `bug.js` does not handle negative numbers correctly due to type coercion.  The solution involves explicitly converting inputs to numbers to ensure accurate calculations.  This highlights the importance of careful type handling in JavaScript.