# Intro to Markdown Lab - Setup

![Hero image](./assets/hero.png)


Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
```
Make a new directory called `intro-to-markdown-lab`, then enter this directory:

```bash
mkdir intro-to-markdown-lab
cd intro-to-markdown-lab
```

Then, create a `README.md`. This file will hold your work for this lab.


```bash
touch README.md
```
With the file created, open the contents of the directory in VS Code:

```bash
code .
```


## Starter Content

For this Lab we'll be applying some Markdown formatting to some existing written content. We've provided that content below. 

Paste the following raw content into your newly created `README.md` file:

```
Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to structure your code, make it more readable, and avoid repetition. Here's a brief guide on creating a function in JavaScript.

1. Basic Syntax

function functionName(parameters) {
    // code to be executed
}

function: The keyword to declare a function.
functionName: The name you choose for the function.
parameters: Optional. Data passed into the function.

Example:

function greet(name) {
    console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a Function

To execute the function, you call or invoke it by using its name followed by parentheses.

Example:

greet('Alice'); // Outputs: Hello, Alice!


3. Return Values

Functions can process data input and output a value using the return keyword.

Example: 

function addNums(numA, numB) {
    return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6


For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
```



## Preview Markdown

VS Code supports Markdown files out of the box. Simply save your document with an .md extension. 
This allows you to effortlessly switch between the code view and a live preview of your Markdown content. 
If you have an existing Markdown document, you can easily open and modify it within VS Code as well.

You can view a preview side-by-side with the file you are editing and see changes reflected in real-time as you edit.

Use these keyboard shortcuts to open a preview tab in VS Code:
 - Mac: **Cmd+K  V**
 - Windows/Linux: **Ctrl+K  V**

***[read the docs](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview)***
