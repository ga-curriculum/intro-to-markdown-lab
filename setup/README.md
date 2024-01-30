# ![Intro to Markdown Lab - Setup](./assets/hero.png)

Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
```

Navigate to [GitHub](https://github.com/) and create a new repository named **intro-to-markdown-lab**.

- Make sure the repo is set to `public`
- You do not need a `README.md`
- You do not need a `.gitignore`

Using the `Quick Setup` option, clone your newly created repo into your `~/code/ga/labs` directory with the `git clone` command:

```bash
git clone https://github.com/<your-username>/intro-to-markdown-lab.git
```

> Note: In the link above, where it says `<your-username>`, you should see the username from your GitHub account.

Next, `cd` into your new cloned directory, `intro-to-markdown-lab`:

```bash
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

For this lab we'll be applying some Markdown formatting to some existing written content. We've provided that content below. 

Paste the following raw content into your newly created `README.md` file:

```
Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

const functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.

Example:

const greet = (name) => {
  console.log("Hello, " + name + "!");
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

Example:

greet('Alice'); // Outputs: Hello, Alice!

3. Return values

Functions can process data input and output a value using the return keyword.

Example: 

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
```

## Preview markdown

VS Code supports Markdown files out of the box. Simply save your document with an .md extension. 
This allows you to effortlessly switch between the code view and a live preview of your Markdown content. 
If you have an existing Markdown document, you can easily open and modify it within VS Code as well.

You can view a preview side-by-side with the file you are editing and see changes reflected in real-time as you edit.

Use these keyboard shortcuts to open a preview tab in VS Code:

- Mac: `⌘ Command` + `K` followed by `V`
- Windows/Linux: `Ctrl` + `K` followed by `V`

***[read the docs](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview)***
