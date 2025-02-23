# JavaScript Addition Function Bug

This repository demonstrates a potential bug in a simple JavaScript addition function and its solution. The function `foo` adds two numbers, but its handling of null and other falsy values needs improvement.

## Bug Description
The original function only explicitly checks for `null` values.  It doesn't consider other falsy values (0, false, "", etc.) which could lead to unexpected results, especially if these values are intended to represent the absence of a numerical input.

## Solution
The solution file provides an improved version of the function that addresses this issue by checking if a value is a number before attempting addition.  This prevents unexpected results arising from the coercion of falsy values to numbers during addition.

## How to run
1. Clone the repository
2. Open `bug.js` to see the original buggy code
3. Open `bugSolution.js` to see the improved version