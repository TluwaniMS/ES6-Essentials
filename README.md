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

The `filter()` method returns new array with all the elements that satisfy the conditions required by the `Callback function` provided.

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `map()`:

The `map()` method returns a new array containing manipulated element properties or specific element properties that are set in the `Callback Function` provided.

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `forEach()`:

The `forEach()` method runs the logic provided in the `Callback Function` on each element in an array

The `Callback Function` is invoked with three arguments:

-> The value of the element

-> The index of the element

-> The array

`ArrayMethod(()=>{/*...*/})` or `ArrayMethod(function(){/*...*/})`
* `reduce()`:

The `reduce()` method runs a reducer `Callback Function` and returns a single value.

The `Callback Function` passed in the reduce method is invoked with four arguments:

-> The previous value

-> The current value

-> The current index

-> The array

`reduce((previousValue,currentValue,currentIndex,array)=>{/*...*/})` or `reduce(function(previousValue,currentValue,currentIndex,array){/*...*/})`

* `sort()`:

The `sort()` method returns an array of sorted elements in ascending or descending order depending on the `Callback Function` passed in.

The `Callback Function` passed in the `sort()` method is invoked with two arguments:

-> `a` the first element for comparison

-> `b` the second element for comparison

`sort((a,b)=>{/*...*/})` or `sort(function(a,b){/*...*/})`

The `sort()` method by default sorts values as strings and sorts them in ascending order;

if ever an array of integers is passed the elements will be converted to strings and sorted according to eacch characters Unicode code point value.

## 5. Javascript Arrow Functions

`Arrow functions` are/offer a shorter way of writing Javascript functions.

## 6. Javascript Sets

A Javascript `set` is an object/collection of unique elements.

* creating a `set`:
* creating a `set` from an array:
* adding an element to a `set`:
* looping a `set`:

## 7. Javascript Default Function Parameters

`Default Function Parameters` serve as initialised arguments that represent default values, that can be used in case no arguments are passed when calling a function.

## 8. Javascript Array Methods

* `concat()`:

The `concat()` method is used to join two array and return only one

* `indexOf()`:

The `indexOf()` method is used to identify the index of an element in an array

* `includes()`:

The `includes()` method is used to check if an array includes a specified element

* `join()`:

The `join()` method is used to join all the elements in an array and return them as a single string

* `push()`:

The `push()` method is used to add new elements to the end of an array

* `splice()`:

The `splice()` method is used to either add or remove elements from an array

## 9. Javascript Destructuring

* How to access object properties:
* How to access object properties and assign a new name to them:
* How to access object properties and assign a new name to them and a default parameter:

## 10. Javascript Template Literals

`Template literals` use backticks  ` `` ` and not quotes `("...")` to create a string;

It allows for one to use various punctuation marks and reference variable values in the string with ease.

## 11. Javascript Switch Statements

The javascript `switch` statement is used to execute/trigger specific functions depending on the conditions that have been given.

## 12. Javascript Ternary Operators

The `Ternary operator` is a simplified/shortened way of writing out a conditional operator `if/else`

## 13. Javascript Spread Operators

The `Spread operator` allows us to join array elements  or object properties into another array or object

## 14. Javascript Promise

A Javascript `Promise` is a representation of a value/data that is still to be.

* `Producing Code`:

Code that is responsible for getting the required values/data

* `Consuming Code`:

Code that must wait for the producer to deliver the required data to be consumed or perform the defined data manipulations

A `Promise` is a Javascript object that links producing and consuming code.

## 15. Javascript setTimeout

The `setTimeout()` method allows the calling of a function, after a certain amount of time

## 16. Javascript setInterval

The `setInterval()` allows us to run a function after a set period of time repeatedly.
