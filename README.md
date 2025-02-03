# JavaScript Loose Equality Bug

This repository demonstrates a common error in JavaScript related to loose equality (==) versus strict equality (===).

## Description
The `bug.js` file contains a function `foo` that uses loose equality to compare its arguments. This can lead to unexpected behavior when comparing values of different types.

The `bugSolution.js` file provides a corrected version of the function that uses strict equality to avoid the type coercion issues.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` in a JavaScript environment.
3. Execute the code. Observe the unexpected behavior.
4. Open `bugSolution.js`. Note the change to use strict equality.
5. Run the code. The corrected version will function as expected.

## Solution
Always use strict equality (===) when comparing values in JavaScript to avoid unexpected type coercion behavior.