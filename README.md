# JavaScript Function with Null/Undefined Handling Bug

This repository demonstrates a common JavaScript bug related to handling null or undefined values in function arguments.  The `foo` function is designed to add two numbers but doesn't robustly handle cases where arguments might be undefined.

## Bug Description

The provided `bug.js` demonstrates a simple addition function. The function correctly handles null values by returning 0. However, if an argument is undefined, it might lead to unexpected behavior or a runtime error (depending on the JavaScript engine).  The solution improves the robustness of the function.

## Solution

The `bugSolution.js` file provides a corrected version of the function that explicitly checks for both null and undefined values, enhancing its reliability and preventing potential errors.