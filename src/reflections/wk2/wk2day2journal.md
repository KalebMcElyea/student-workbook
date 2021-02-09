
What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

Function Declaration: Defines a named function. This allows the function to be hoisted so it allows us to use this function before it's defined. 

Function Expression: Defines a named or anonymus function. Function expression are not hoisted so it MUST be defined before used.

Arrow Function Expression: Is a shorter syntax for writing function expression. The only thing that was written for an Arrow function expression is that arrow functions do not create their own "this" value


What is the difference between Parameters and Arguments?

Parameters are a placeholder.
Arguments are the value the function recieves. 

What are higher order functions? Can you provide an example?

When a function accepts another function as a parameter or even returns as a function it's known as a high order function. One exmaple is Array.prototype.filter 
