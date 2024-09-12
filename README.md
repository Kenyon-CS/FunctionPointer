# FunctionPointer
C++ program to pass function as a pointer to any function

This C++ program demonstrates how to pass a function pointer to another function and use it to invoke different operations like addition, multiplication, and raising a number to a power.

## Explanation:
1. Function Definitions:

  - `add`: Takes two integers, returns their sum.
  - `multiply`: Takes two integers, returns their product.
  - `power`: Takes two integers, raises the first integer to the power of the second using the `pow` function from `<cmath>`.
2. Function Pointer:

  - The `invoke` function takes three parameters: two integers (`x` and `y`) and a pointer to a function that accepts two integers and returns an integer.
  - The `invoke` function uses the passed function pointer (`func`) to apply the operation on the arguments `x` and `y`.
3. Main Function:

  - Calls the `invoke` function three times, passing function pointers for `add`, `multiply`, and `power` to perform respective operations.
  - The result of each operation is printed.
