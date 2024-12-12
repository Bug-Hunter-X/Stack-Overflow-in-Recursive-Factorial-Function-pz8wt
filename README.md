# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow due to excessive recursion depth.  The `foo` function calculates the factorial using recursion.  For large inputs, this leads to exceeding the program's stack size limit.  The solution demonstrates a more efficient iterative approach, avoiding the stack overflow.

## Bug Description:
The recursive factorial function `foo` does not optimize the base case resulting in stack overflow error for larger inputs. 

## Solution:
The provided solution replaces the recursive solution with an iterative solution, eliminating the risk of a stack overflow error for large input values. 
