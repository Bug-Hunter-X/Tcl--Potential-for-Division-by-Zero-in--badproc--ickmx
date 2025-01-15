# Tcl: Potential Division by Zero

This repository demonstrates a common error in Tcl: a potential for division by zero.  The `bug.tcl` file contains a procedure that fails to handle this case properly, leading to a runtime error.  The `bugSolution.tcl` file shows a corrected version.

## How to reproduce

1.  Save the code in `bug.tcl`.
2.  Run the script using a Tcl interpreter (e.g., `tclsh bug.tcl`).

## Solution

The solution involves adding an explicit check for division by zero before performing the division operation.  The improved code is available in `bugSolution.tcl`.