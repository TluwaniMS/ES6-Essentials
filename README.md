# ES6-Essentials

## 1. Javascript Hoisting
Hoisting is when the Javascript file interpreter moves all the functions, variables, and class declarations to the top of the file before any of the code is executed.
## 2. Javascript Scopes
There are 3 types of scopes in Javascript:
* The Global Scope:

This refers to variables declared outside of a function, these variables can be accessed from anywhere within the file.
* The Function Scope:

This refers to variables that are declared inside/within a function; these variables can only be accessed within the function.
* The Block Scope:

This refers to functions that are declared inside curly braces `{}` (a block).
Variables declared in these blocks can not be accessed/used outside of the blocks.
## 3. Javascript Variable Declarers

* `var`:

Variables that are declared with the `var` keyword can be accessed in any scope of the file. 

-> Variables declared with `var` can be redeclared

-> Variables defined with `var` must be declared before use

-> Variables defined with `var` are not limited to a block or function scope

-> Variables defined with `var` can be reassigned.
* `let`:

Variables that are declared with the `let` keyword are limited within the scope that they are declared in.

-> Variables declared with `let` can not be redeclared

-> Variables defined with `let` must be declared before use

-> Variables defined with `let` are limited to a block or function scope

-> Variables defined with `let` can be reassigned.
* `const`:

Variables that are declared with the `const` keyword are limited within 

-> Variables declared with `const` can not be redeclared

-> Variables defined with `const` must be declared before use

-> Variables defined with `const` are limited to a block or function scope

-> Variables defined with `const` can not be reassigned.
## 4. Javascript Higher Order Array Functions

`NB!` What are `Higher Order Functions`:

`Higher Order Functions` are functions that take in other functions as arguments or return functions.

`Javascript Higher Order Array Functions` call a `Callback Function` for each element in the array provided and return an array of values;
excluding `reduce()`.

* `filter()`:

The `filter()` returns new array with all the elements that satisfy the conditions required by the `Callback function` provided.

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `map()`:

The `map()` returns a new array containing manipulated element properties or specific element properties that are set in the `Callback Function` provided.

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `forEach()`:

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `reduce()`:
* `sort()`:
## 5. Javascript Arrow Functions
## 6. Javascript Sets
## 7. Javascript Default Function Parameters
## 8. Javascript Array Methods
## 9. Javascript Destructuring
## 10. Javascript Template Literals
## 11. Javascript Switch Statements
## 12. Javascript Ternary Operators
## 13. Javascript Spread Operators
## 14. Javascript Promise
## 15. Javascript setTimeout
## 16. Javascript setInterval
