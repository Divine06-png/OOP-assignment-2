Name: Divine phillip
Reg #: 2420011


This assignment demonstrates key concepts in C programming, including arrays, pointers, pointer arithmetic, and function pointers.

* Arrays and Pointers
Arrays store multiple values in a single variable.
In C, the name of an array acts like a pointer to its first element.
Elements can be accessed using:

Array indexing → arr[i]
Pointer arithmetic → *(arr + i)
Both methods produce the same result.

 *Pointer Arithmetic
Pointers can move through memory using addition or subtraction.
Example:

*(arr + 2) accesses the 3rd element.
arr[-2] can access elements before the current pointer position.
This shows how memory is accessed directly using pointers.

* Arrays Passed to Functions
When an array is passed to a function, it is passed as a pointer.
Any changes made inside the function affect the original array.

Example: modifying array values using a loop inside a function.

* Function Pointers
Functions have memory addresses just like variables.
A function pointer stores the address of a function and allows it to be called indirectly.

Example:
fPtr = adder;
fPtr(10, 20);

* Passing Functions as Arguments
Functions can be passed as parameters to other functions using function pointers.
This allows one function to perform different operations depending on the function passed.

Example: a function that can either add or divide numbers based on the function pointer.

* Returning Functions from Functions
Functions can return pointers to other functions.
This allows dynamic selection of which function to execute at runtime.
