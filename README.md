# PHP Notice: A non-numeric value encountered
This repository demonstrates a common PHP error: "A non-numeric value encountered."  The `calculateSum()` function attempts to add up numbers in an array. However, if the array contains a non-numeric value, PHP generates a warning, and the result is incorrect.

The `bug.php` file shows the problem.  The solution, in `bugSolution.php`, demonstrates how to handle this using `is_numeric()` for robust error handling.