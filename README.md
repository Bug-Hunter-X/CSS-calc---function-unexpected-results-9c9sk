# CSS calc() Unexpected Results

This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to operator precedence or unit mismatches. 

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file shows how to correct the issue by explicitly specifying units and using parentheses to control the order of operations.  Remember, all terms within a `calc()` expression must have explicit units (such as `px`, `%`, `em`, etc.).