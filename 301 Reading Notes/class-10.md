What is a ‘call’?
* A call is an invocation of a function.

How many ‘calls’ can happen at once?
* The Javascript call stack, only one call is invoked at a time.

What does LIFO mean?
* LIFO (Last In, First Out) means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack. Here is an example of a call stack that divides the product of two number by 2:

```javascript
function multiply(a, b) {
    return a * b;
}
function average(a, b) {
    return multiply(a, b) / 2;
}

let x = average(10, 20);
```

What causes a Stack Overflow? 
Stack overflow is when a function that calls itself, without an exit point. 
JavaScript error messages.

What is a ‘reference error’?
* A reference error is thrown when you try to use a variable that is not yet declared

What is a ‘syntax error’?
* A syntax error is thrown something that cannot be parsed because of incorrect syntax.

What is a ‘range error’?
* A range error is thrown when an invalide length is returned.

What is a ‘type error’?
* A type error is thrown when the types (number, string and so on) you are trying to use or access are incompatible.

What is a breakpoint?
* A breakpoint is a condition that will cause a break in code.

What does the word ‘debugger’ do in your code?
* The keyword debugger invokes any available debugging functionality, such as setting a breakpoint.


References
* https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors
