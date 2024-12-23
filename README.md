# CSS calc() Unexpected Behavior
This repository demonstrates a common issue with the CSS `calc()` function: unexpected results when combining percentages and fixed units, and inconsistencies in calculations involving multiple units and complex expressions.

The `bug.css` file contains the problematic CSS code.  The `bugSolution.css` demonstrates a solution to resolve these issues.

## Problem
The main problem lies in how `calc()` interacts with percentages when the parent element's dimensions are not yet fully determined. Also, the order of operations might not be intuitive in complex calculations.