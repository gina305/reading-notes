# Functional Programming Concepts

What is functional programming?
* Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data 

What is a pure function and how do we know if something is a pure function?
* A pure function returns the same result if supplied the same arguments. It does not cause any observable side effects. Pure functions do not read external files. For example, the math.random method is pure. Pue functions are stable, consistent and predictable.

What are the benefits of a pure function?
* Pure functions make code easier to test.This is because a pure function will always have the same output, given the same input.

What is immutability?
* Immutability is the inability to change an object’s state, once the object is created.

What is Referential transparency?
* Referential transparency is the fact that a functions yields the same result for the same input. 
________________________________________________

What is a module?
* A module is a javascript file that performs a function.

What does the word ‘require’ do?
 * Require is a builtin function that reads and executes code in a Javascript file, then returns the exports object.
 
How do we bring another module into the file they we are working in?
* You must first import the module, using the ‘require’ function.

What do we have to do to make a module available?
* To make a module available, you need to export it using the ‘exports’ keyword.
