# Hack: Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in Hack: stack overflow due to unbounded recursion. The `foo` function calculates the factorial recursively, which can lead to a stack overflow if the input `x` is too large.

The provided solution shows an iterative approach to factorial calculation, effectively avoiding stack overflow errors.

## Bug

The bug lies in the recursive nature of the `foo` function.  For large inputs, the call stack grows without bound, exceeding the system's limit and resulting in a stack overflow.

## Solution

The solution replaces the recursive implementation with an iterative one, using a loop to compute the factorial. This approach prevents stack overflow by eliminating the unbounded recursive calls.