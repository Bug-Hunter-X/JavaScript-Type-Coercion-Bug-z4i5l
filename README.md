# JavaScript Type Coercion Bug
This repository demonstrates a common JavaScript bug related to type coercion.  The `foo` function attempts to add a number and a string. JavaScript's loose typing allows this, but the result is unexpected string concatenation instead of numerical addition.
The `bug.js` file contains the buggy code, while `bugSolution.js` demonstrates the corrected version using explicit type checking or conversion.

## How to reproduce
1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment (e.g., Node.js, browser console).
3. Observe the unexpected output.
4. Compare the result to the corrected version in `bugSolution.js`.