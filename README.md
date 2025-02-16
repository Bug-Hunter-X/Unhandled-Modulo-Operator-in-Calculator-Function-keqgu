# Unhandled Modulo Operator in Calculator Function

This repository demonstrates a common JavaScript error: unhandled cases in a switch statement. The `operate` function performs basic arithmetic operations, but it lacks handling for the modulo operator (`%`). This results in an error when the modulo operator is used.

The `bug.js` file contains the original code with the error. The `bugSolution.js` file provides the corrected code that adds handling for the modulo operator.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` in a text editor or IDE.
3. Run the script using Node.js or your preferred JavaScript environment. Observe the error when using the modulo operator.
4. Open `bugSolution.js`. Observe how the solution extends the switch statement to handle the modulo operator.

## Solution

The solution involves adding a `case '%' ` to the existing switch statement in the `operate` function to handle the modulo operation. 