<h1>
  <span class="headline">Intro to Markdown Lab</span>
  <span class="subhead">Exercise</span>
</h1>

Markdown is a lightweight, intuitive language designed for formatting text. Whether you're jotting down notes, drafting a blog, or collaborating on a coding project, Markdown streamlines your writing process. Its simple syntax emphasizes content over intricate formatting, making your text clean and readable. It's quickly becoming a must-know language in both the tech and writing worlds. 

Markdown is frequently used for crafting documentation and coding tutorials. Sites like Github host entire bodies of curriculum written in this format. You're reading one right now.
 
## Your tasks

We'll guide you through creating a Markdown file in this two-part lab.

### Part 1 

While exploring this new syntax, we'll practice applying Markdown formatting to a short coding tutorial: ***How to Write a Function in JavaScript***. The raw text content for this tutorial has been provided in the setup for this lab. 

### Part 2

By the end of this exercise, you'll have a finished sample Markdown document, and all the tools you'll need to ***create another short tutorial on a topic of your choice***. 

Let's explore! 

## Part 1: Applying styles in Markdown

### 1. Headers 

Headers in Markdown are used to create titles and subtitles, much like how they work in HTML. They provide structure to your document, making it easier to read and navigate.

To create headers in Markdown, you use the `#` symbol followed by a space and the title of your header. The number of `#` symbols determines the level of the header. For example:

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

> 🤯 Markdown is supported by numerous platforms, including GitHub, Stack Exchange, Reddit, and many blogging platforms, making it an essential skill for developers and writers.

---

### 🧠 You Do: Format your headers

Find the main and section titles in your `README.md`. Apply the correct `#` header syntax to give these sections the proper hierarchy.

Use these keyboard shortcuts to open a preview tab in VS Code:

- Mac: `⌘ Command` + `K` followed by `V`
- Windows/Linux: `Ctrl` + `K` followed by `V`

---

### 2. Text styles

The three most common ways to format text in Markdown are **Bold**, *Italics*, or ***Both***. 

#### Bold

Embolden text by wrapping it in with two `**` or `__`.

```
This text is **bold**. This text is also __bold__.
```

<!-- Markdown Preview -->
This text is **bold**. This text is also __bold__.
<!-- End Preview -->

#### Italic

Italicize text by wrapping it with `*` or `_`.

```
This text is in *italics*. This text is also in _italics_.
```

<!-- Markdown Preview -->
This text is in *italics*. This text is also in _italics_.
<!-- End Preview -->

#### Italic and bold

Combine italic and bold by adding a third `*` or `_`.

```
This text is ***bold and italicized***. This text is also ___bold and italicized___.
```

<!-- Markdown Preview -->
This text is ***bold and italicized***. This text is also ___bold and italicized___.
<!-- End Preview -->

> 🤯 Markdown can be easily converted to various output formats, including HTML, PDF, and Word, ensuring consistent and clean formatting.

---

### 🧠 You Do: Format some text

1. Find the **"Basic syntax"** section in your `README.md` file. Look for these five lines describing the syntax of arrow functions:

   ```
   const: ...
   The function name: ...
   Parameters: ...
   The arrow syntax: ...
   The body: ...
   ```

2. Make all the words before the colons (`:`) on each line **bold**. 

3. In the **"Calling a function"** section, make the words "call" and "invoke" *italicized*. This signals that these are new vocabulary words that require *emphasis*. 

4. Do the same for the word "return", when it's introduced in the **"Return values"** section.

5. Above each code snippets you'll find the word "Example:" Format these as **bold**, *italic*, or ***both***. You choose. 

---

### 3. Creating lists

Lists are a foundational aspect of structuring content, offering a clear way to present a series of related items in an organized way. Both are very easy to format in Markdown.

#### Bulleted lists: unordered lists
To create a bulleted list, you can use asterisks (`*`), plus (`+`), or minus (`-`) followed by a space. These symbols act as bullet points:

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


#### Numbered lists: ordered lists

For numbered lists, use numbers followed by a period and a space:

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

> 💡 Markdown handles the numbering automatically, so you can use `1.` for every item, and the numbers will still increment correctly. Try it. 

---

### 🧠 You Do: Make a list

In the **"Basic syntax"** section, find the five components of syntax again (we made them bold earlier). Format them as an ordered or unordered list.

---

### 4. Code snippets

Code snippets are invaluable in technical documentation, allowing readers to view, understand, and copy code directly from the Markdown. 

#### Inline code

For short, ***inline*** code references, wrap the word or code with backticks (`` ` ``).

This syntax: 

```
Use the `console.log()` function to print values to the console.
```

Produces this formatting: 

<!-- Markdown preview -->
Use the `console.log()` function to print values to the console.
<!-- End preview -->

Inline code formatting can also be used to highlight text that should stand out, such as file names `index.html`, special characters `>` `%` `+`, or anything else you need to call attention to in the middle of a sentence. 

#### Multi-line code blocks

To present multi-line code snippets or blocks, use three backticks `` ``` `` consecutively as an opening and closing syntax. To enhance readability, you can also specify the programming language right after the first three backticks, enabling markdown syntax highlighting.

This syntax:

````
```javascript
const printItem = (item) => {
  console.log(item);
}
```
````

Produces this formatting: 

<!-- Markdown preview -->
```javascript
const printItem = (item) => {
  console.log(item);
}
```
<!-- End preview -->

> 💡 Many popular programming languages have syntax highlighting. Some valid options include `javascript`, `python`, `css`, `html`, and more!

---

### 🧠 You Do: Create code blocks

Locate the code snippets in each of the content sections of your `README.md`. Apply the correct markdown syntax to format them as language-highlighted code blocks.

---

### 5. Adding links

Links in Markdown are a straightforward way to reference external resources or provide links to other pages in your documentation. 

#### Inline-style links

You can create an inline link by wrapping the link text in brackets `[My URL]`, followed by the URL in parentheses `(www.myurl.com)`.

This syntax:

```
[Google](https://www.google.com)
```

Produces this formatting: 

<!-- Markdown preview -->
[Google](https://www.google.com)
<!-- End preview -->

#### Reference-style links

For better readability, or if you're referencing the same link multiple times to cite a source, you can use reference-style links:

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

> 🤯 Incorporating Markdown into your skill set can open doors to various professional and collaborative opportunities. Many junior developers get their start in technical writing jobs.

---

### 🧠 You Do: Cite the docs

Locate the link to the MDN page at the bottom of the `README.md`, and format it as an inline style link.

---

### 6. Blockquotes

Blockquotes are handy for highlighting important asides in text, often representing citations, referenced content, or emphasizing statements in your Markdown documents.

To create a blockquote, start the line with the `>` character followed by a space.

This syntax:

```
> This is a blockquote.
```

Produces this formatting:

<!-- Markdown preview -->
> This is a blockquote.
<!-- End preview -->

You can also nest blockquotes by using additional `>` characters.

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

Blockquotes can contain other Markdown formatted elements, like `headers`, `lists`, or even other `blockquotes`. Try it out. 

---

### 🧠 You Do: Create a blockquote

Locate the helpful "Tip:" at the end of the **"Basic syntax"** section in your `README.md`. Format this text as a blockquote.

---

### 7. Adding images

Using images can elevate your documentation, tutorials, and project write-ups. Embedding images is straightforward in Markdown (and the best way to include screenshots in a project).  

#### Hosted image embedding

The syntax to embed an image is like creating a hyperlink in Markdown, but it's prefixed with an exclamation mark `!`.

This syntax:

```
![some alt text](www.url_to_an_image.com/image)
```

Produces an image:

<!-- Markdown preview -->
![some alt text](www.url_to_an_image.com/image)
<!-- End preview -->

Wait, why is there no image? Because we did not include an ***actual*** URL in this example, you'll see a **broken image placeholder** with the alt text displayed. This same placeholder is displayed whenever there is a problem loading an image. This could be caused by a poor internet connection or the image location has changed.

> 💡: Always use descriptive ***alt text***. Alt text, short for "alternative text," is a descriptive text added to an image's HTML tag on websites and other digital platforms. Its primary purpose is to provide a clear description of the image's content for those who cannot view it directly. Screen readers, search engines, and slow internet connections depend on this text to provide context.

Now let's view a real example.

The syntax:

```
![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
```

And the resulting image:

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

#### Using relative image paths

If your image is stored in the same repo as your Markdown file, you can use a relative path instead of a URL.

This uses the same syntax, just with a local file path: 

```
![Computer with Code](./assets/james-harrison-unsplash.jpg)
```

In this example, the image `james-harrison-unsplash.jpg` is in an `assets` folder in the same directory as this Markdown document.

---

### 🧠 You Do: Add an image

Let's source an image from the web and include it in our markdown file. We'll be sourcing an image from Unsplash, a website that offers high-quality, royalty-free images. 

1. Open a new browser tab and navigate to [Unsplash](https://unsplash.com/).

2. Use the search bar or browse through the categories to find an image you'd like to include in your Markdown file. Let's find something that might be a nice banner image for our tutorial- to draw readers in!

*To use a hosted image:*

3. Select an image to open it. Right-click on the image and select **Copy image address** to copy the image URL.

4. Link to the image using a URL.

```
![some alt text](www.url_to_an_image.com/image)
```

*To use a downloaded image:*

3. Select an image to open it. Choose the download option and select an image size. 

3. Find the image in your downloads folder and move it into the directory with your markdown file. 

4. Link to the image using a relative file path. 

```
![some alt text](./the-name-of-my-image.jpg)
```

---

### 8. Extended syntax

A handful of extended features in Markdown are not supported on all platforms. Here are a few of our favorite elements. 

#### Tables

Here's the table syntax:

```
| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |
```

And what this shows up as:

<!-- Markdown preview -->
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
<!-- End preview -->

#### Task lists

```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

<!-- Markdown preview -->
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
<!-- End preview -->

#### Strikethrough

```
This text has been ~~redacted~~. 
```

<!-- Markdown Preview -->
This text has been ~~redacted~~. 
<!-- End Preview -->

<br><br>

## Let's check your work

Compare your `README.md` **preview** to the rendered Markdown below. Make any needed adjustments to match this formatting. Solution code will be provided. 

<br><br>

# Writing a Function in JavaScript

![Computer with Code](./assets/james-harrison-unsplash.jpg)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

- **const**: const should be used whenever a function expression is assigned to a variable.
- **The function name**: The name you choose for the function.
- **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
- **The arrow syntax**: Indicates that this will be a function.
- **The body**: The statements that make up the function itself. Surrounded by curly braces.

*Example*:

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

*Example:*

```javascript
greet('Alice'); // Outputs: Hello, Alice!`
```

## 3. Return values

Functions can process data input and output a value using the *return* keyword.

*Example:* 

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).

<br>

## Part 2: Create another tutorial ( 30 min )

1) Create a new file with a `.md` extension.

2) Choose a new topic, we've provided a few for inspiration:

   - How to write an HTML Boilerplate
   - The anatomy of a CSS selector
   - How to create a file using the Terminal
   - How to build the perfect sandwich

3) Practice your new skills by writing another short tutorial in Markdown!
