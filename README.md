# Unexpected String Concatenation in JavaScript
This repository demonstrates a common JavaScript bug caused by the language's loose typing system. Specifically, it shows how attempting to add a number and a string results in unexpected string concatenation instead of the expected arithmetic addition.

## The Bug
The `bug.js` file contains a function `foo` that attempts to add two inputs. However, if one input is a string, JavaScript will perform string concatenation instead of addition.

## The Solution
The `bugSolution.js` file corrects this behavior by explicitly converting the inputs to numbers using `parseInt` or `parseFloat` before performing the addition. This ensures the correct numerical result.

## How to Reproduce
1. Clone this repository.
2. Run `bug.js` using a JavaScript interpreter (e.g., Node.js).
3. Observe the incorrect output.
4. Run `bugSolution.js` to see the corrected output.