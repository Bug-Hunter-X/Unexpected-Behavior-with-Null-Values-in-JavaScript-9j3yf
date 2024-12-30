# Unexpected Behavior with Null Values in JavaScript

This repository demonstrates a common error in JavaScript related to handling null values.  The code in `bug.js` shows a function that correctly handles null inputs using strict equality (`===`).  However, this example highlights the importance of using strict equality to prevent unexpected behavior when comparing values, especially `null`.  The solution, provided in `bugSolution.js`, showcases best practices for robust null handling.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js` in your terminal.