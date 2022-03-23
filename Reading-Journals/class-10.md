# Ch. 10, “Error Handling & Debugging”

## What is debugging?
Debugging is the process of finding errors through the use of deduction.

For JavaScript errors, the console will display information about errors in you code and where it occurred.


## What to use to find errors in code?

To find errors, you can use:

* Browser developer tools to inspect your webpage for information and errors (such as Google's built-in inspect tool).
* Use conditional breakpoints such as a breakpoint defined with the debugger keyword to identify whether a condition is met or not.
* Use the console.assert( ) method to test whether an expression is met. Also other console methods such as:
 * '''console.info( )''',
 * '''console.warn( )''',
 *'''console.error( )''', etc…
To make it easier to find errors in your code, what should you understand about code execution?

## How to identify errors?

### Order of Execution
Understanding how JS code is executed helps you better identify errors. First think of the order of execution. For example, when dealing with return statements in functions, keep in mind that the value returned from a function will be sent to the source that it was called from.


### Execution Context & Scope
To identify eros, it also helps to know where the script you write "lives". In most cases code is either executed in global context/scope or function context/scope.  If the value of a variable is assigned to the result of a function, that function is prioritized in the stack. This prioritization is called hoisting, which allows you to assign a function's value to a variable even if it has not been declared before  it's use.


## How to handle errors?
Statements such as '''try''', '''catch''' and '''finally''' can be used to gracefully handle errors.
