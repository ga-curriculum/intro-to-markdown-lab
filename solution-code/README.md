```
# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing a function in JavaScript.

## 1. Basic Syntax

'''javascript
function functionName(parameters) {
    // code to be executed
}
'''

 - **function**: The keyword to declare a function.
 - **functionName**: The name you choose for the function.
 - **parameters**: Optional. Data passed into the function.

*Example*:

'''javascript
function greet(name) {
    console.log("Hello, " + name + "!");
}
'''

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a Function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

*Example:*

'''javascript
greet('Alice'); // Outputs: Hello, Alice!`
'''


## 3. Return Values

Functions can process data input and output a value using the *return* keyword.

*Example:* 

'''javascript
function addNums(numA, numB) {
    return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
'''


For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions). 

```