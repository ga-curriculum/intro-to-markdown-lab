# Intro to Markdown Lab - Lab Exercise

![Hero image](./assets/hero.png)

Markdown is a lightweight, intuitive language designed for formatting text. Whether you're jotting down notes, drafting a blog, or collaborating on a coding project, Markdown streamlines your writing process. With its simple syntax, it emphasizes content over intricate formatting, making your text clean and readable. It's quickly becoming a must-know language in both the tech and writing worlds. 

Markdown is frequently used for crafting documentation and coding tutorials. Sites like Github host entire bodies of curriculum written in this format. You're reading one right now.

 
## Your Task

In this lab, we'll guide you through the basics of creating a Markdown file.

 - While exploring this new syntax we'll practice applying some markdown formatting to a simple coding tutorial: ***"How to Write a Function in JavaScript"***. 

 - By the end of this lab, you'll have a polished Markdown sample document, and all the tools you'll need to ***create another markdown document on a topic of your choice***. 

Let's explore! 

## 1. Headers 

Headers in Markdown are used to create titles and subtitles, much like how they work in HTML. They provide structure to your document, making it easier to read and navigate.

To create headers in Markdown, you use the `#` symbol followed by a space and the title of your header. The number of `#` symbols determines the level of the header.

**Example:**

`#` creates an `<h1>` element

This syntax:

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

Creates this formatting: 

<!-- Markdown Preview -->
# h1
## h2
### h3
#### h4
##### h5
###### h6
<!-- End Preview -->

<hr>

### You Do: Format your headers. 

1) Find the main and section titles in your `README.md`. Apply the correct `#` header syntax to give these sections the proper hierarchy.

Use these keyboard shortcuts to open a preview tab in VS Code:
 - Mac: **Cmd+K  V**
 - Windows/Linux: **Ctrl+K  V**
<hr>

> *Did you know* :  Markdown is supported by numerous platforms, including GitHub, Stack Exchange, Reddit, and many blogging platforms, making it an essential skill for both developers and writers.


## 2. Text Styles

The three most common ways to format text in markdown is: **Bold**, *Italics*, or ***Both***. 

### Italic

1) Italicize text by wrapping it with `*` or `_`.
```
This text is in *italics*. This text is also in _italics_.
```
<!-- Markdown Preview -->
This text is in *italics*. This text is also in _italics_.
<!-- End Preview -->

### Bold

2) Embolden text by wrapping it in with two `**` or `__`.
```
This text is **bold**. This text is also __bold__.
```
<!-- Markdown Preview -->
This text is **bold**. This text is also __bold__.
<!-- End Preview -->

### Italic and Bold

3) Combine italic and bold by adding a third `*` or `_`.
```
This text is ***bold and italicized***. This text is also ___bold and italicized___.
```
<!-- Markdown Preview -->
This text is ***bold and italicized***. This text is also ___bold and italicized___.
<!-- End Preview -->

<br>
<hr>

### You Do: Format some text

1) Find the "Basic Syntax" section in your `README.md` file. Look for the three components of syntax.
```
  function: ...
  functionName: ...
  parameters: ...
```
2) Make these words **bold**. 


3) In the "Calling a Function" section, make the words "call" and "invoke" *italicized*. This signals that these are new vocabulary words that require *emphasis*. 

4) Do the same for the word "return" where it is introduced in the "Return Values" section.

5) Above each of the code snippets you'll find the word "Example:" Format each of these as either **bold** or *italic*. You choose. 
  
<hr>

> *Did you know*: Markdown can be easily converted to a variety of output formats, including HTML, PDF, and Word, ensuring consistent and clean formatting.

<br>

## 3. Creating Lists

Lists are a foundational aspect of structuring content, offering a clear way to present a series of related items in an organized way. Both are very easy to format in markdown.

### Bulleted Lists : Unordered Lists
To create a bulleted list, you can use either asterisks `*`, plus `+`, or minus `-` followed by a space. These symbols act as bullet points:

```
* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1
```

This will render as:

<!-- Markdown preview -->
* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1
<!-- End preview -->


### Numbered Lists : Ordered Lists

For numbered lists, simply use numbers followed by a period and a space:

```
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
```
This will produce:

<!-- Markdown preview -->
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
<!-- End preview -->


> **Tip**: Markdown handles the numbering automatically, so you can use 1. for every item, and it will still increment correctly. Try it. 

<hr>

### You Do: Make a list

1) In the "Basic Syntax" section, find the three components of syntax again (we made them bold). Format them as an ordered or unordered list.

<hr>

> *Did you know*: Incorporating Markdown into a student's skill set can open doors to various professional and collaborative opportunities - many junior developers get their start in technical writing jobs.


<br>

## 4. Code Snippets

Code snippets are invaluable in technical documentation, allowing readers to view, understand, and copy code directly from the markdown. 

### Inline Code

For short, ***inline*** code references, wrap the word or code with backticks ( ` ).

This syntax: 

```
Use the `console.log()` function to print values to the console.
```

Produces this formatting: 

<!-- Markdown preview -->
Use the `console.log()` function to print values to the console.
<!-- End preview -->

Inline code formatting is also frequently used to "highlight" text that should stand out, such as file names `index.html`, special characters `>` `%` `+`, or anything else you need to call attention to in the middle of a sentence. 

### Multi-line Code Blocks

To present multi-line code snippets or blocks, use three backticks ( ``` ) consecutively as an opening and closing syntax. To enhance readability, you can also specify the programming language right after the first three backticks, enabling markdown syntax highlighting.

This syntax:
```
'''javascript
function printItem(item) {
  console.log(item)
}
'''
```

Produces this formatting: 
<!-- Markdown preview -->
```Javascript
function greet(name) {
  console.log("Hello, " + name + "!");
}
```
<!-- End preview -->

> **Tip** : Popular programming languages supported for syntax highlighting include javascript, python, ruby, html, and many more!


<hr>

### You Do: Create Code Blocks

1. Locate the code snippets in each of the content sections. Apply the correct markdown syntax to format them as language highlighted code blocks.

<hr>

<br>

## 5. Adding Links

Links in markdown are a straightforward way to reference external resources or provide links to other pages in your documentation. 


### Inline-style Links
You can create an inline link by wrapping link text in brackets `[My URL]`, and then wrapping the URL in parentheses `(www.myurl.com)`.


This syntax:
```
[Google](https://www.google.com)
```

Produces this formatting: 
<!-- Markdown preview -->
[Google](https://www.google.com)
<!-- End preview -->


### Reference-style Links

For better readability, or if you're referencing the same link multiple times to site a source, you can use reference-style links:

This syntax:
```
This is [a reference][example].

[example]: http://www.example.com/
```

Produces this formatting: 
<!-- Markdown preview -->
This is [a reference][example].

[example]: http://www.example.com/
<!-- End preview -->


<hr>

### You Do: Site the Docs

1. Locate the link to the MDN page at the bottom of the `README.md`, format this as an inline style link. 

<hr>

<br>

## 6. Blockquotes

Blockquotes are handy for highlighting important asides in text, often representing citations, referenced content, or emphasizing statements in your Markdown documents.

To create a blockquote, you start the line with the `>` character followed by a space.

This syntax:
```
> This is a blockquote.
```

Produces this formatting: 
<!-- Markdown preview -->
> This is a blockquote.
<!-- End preview -->

You can also nest blockquotes by using additional `>` characters:

This syntax:
```
> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.
```

Produces this formatting: 
<!-- Markdown preview -->
> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.
<!-- End preview -->

Blockquotes can contain other Markdown formatted elements, like headers, lists, or even other blockquotes. Try it out. 

<hr>

### You Do: Create a Blockquote

1. Locate the helpful "Tip:" at the end of the "Basic Syntax" section. Format this text as a blockquote. 

<hr>
<br>

## 7. Adding Images

Using images can elevate your documentation, tutorials, and project write-ups. Embedding images is very easy in Markdown (and the best way to include screen shots of your projects!)  

### Hosted Image Embedding

To embed an image, the syntax is almost like creating a hyperlink in Markdown, but it's prefixed with an exclamation mark `!`.

This syntax:
```
![Alt Text](www.fake_url_to_an_image.com/image)
```

Produces an image: 
<!-- Markdown preview -->
![Alt Text](fake_URL_to_an_image)
<!-- End preview -->

Because no ***actual*** URL was linked in this example, you'll see a **broken image placeholder** with the alt text displayed.

> **Tip**: Always use descriptive ***alt text***. Alt text, short for "alternative text," is a descriptive text added to an image's HTML tag on websites and other digital platforms. Its primary purpose is to provide a clear description of the image's content for those who cannot view it directly. Screen readers, search engines, and slow internet connections depend on this text to provide context.

### Using Relative Paths

If your image is stored in the same repository or directory as your Markdown file, you can use relative paths instead of full URLs:

This syntax: 

```
![Function Diagram](./assets/functions_addNums.png)
```

Produces this image: 
<!-- Markdown preview -->
![Function Diagram](./assets/functions_addNums.png)
<!-- End preview -->

Here, the image `functions_addNums.png` is in an `assets` folder in the same directory as this Markdown document.


<hr>

### You Do: Add an image

1. Right click the image above and download it to your computer.

2. Place the image in the same folder as your `README.md` file. 

3. Replace the code snippet in the "Return Values" section with this colorful image instead. 

<hr>
<br>

## Extended Syntax

There are a handful of extended features in markdown that are not supported in all platforms.
Here are a few of our favorite elements. 

**Tables**


```
| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |
```

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


**Task Lists**


```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

- [x] Task 1
- [ ] Task 2
- [ ] Task 3


**Highlight**

```
Look a ==color== other than gray! 
```

Look a ==color== other than gray! 


**Sub Script**

```
H~2~O
```

H~2~O

**Super Script**

```
X^2^
```
X^2^

**Strikethrough**

```
This text has been ~~redacted~~. 
```
<!-- Markdown Preview -->
This text has been ~~redacted~~. 
<!-- End Preview -->
<br> 


# Let's check your work


Compare your `README.md` to the Markdown below: 


<hr>

# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing a function in JavaScript.

## 1. Basic Syntax

```javascript
function functionName(parameters) {
    // code to be executed
}
```

 - **function**: The keyword to declare a function.
 - **functionName**: The name you choose for the function.
 - **parameters**: Optional. Data passed into the function.

*Example*:

```javascript
function greet(name) {
    console.log("Hello, " + name + "!");
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a Function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

*Example:*

```javascript
greet('Alice'); // Outputs: Hello, Alice!`
```


## 3. Return Values

Functions can process data input and output a value using the *return* keyword.

*Example:* 

![image](./assets/functions_addNums.png)


For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions). 

<hr> 
<br>

## You Do: Create another tutorial ( 30 min )

1) Create a new file with a `.md` extension.

2) Choose a new topic, we've provided a few for inspiration:

   - How to write an HTMl Boilerplate
   - The anatomy of a CSS selector
   - How to create a file using the Terminal
   - How to build the perfect sandwich

3) Practice your new skills by writing a tutorial in Markdown.