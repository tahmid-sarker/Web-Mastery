## JavaScript

Welcome! I'm **[Md. Tahmid Sarker Mahi](https://tahmid-sarker.github.io)**, and these are my JavaScript notes. As I journeyed through understanding JavaScript, I documented various concepts, insights, and tips that I found particularly helpful.

> [!IMPORTANT]\
This is not a comprehensive guide to JavaScript. Instead, it's my personal notes on JavaScript. I hope you find them helpful.

## Table of  Contents

1. [Introducing JavaScript](#introducing-javascript)
  - [Importance](#importance)
  - [What is JavaScript?](#what-is-javascript)
  - [What is a scripting language?](#what-is-a-scripting-language)
  - [What can you do with JavaScript?](#what-can-you-do-with-javascript)
  - [Where does the JavaScript code run?](#where-does-the-javascript-code-run)
  - [Who are using JavaScript?](#who-are-using-javascript)
  - [History of JavaScript](#history-of-javascript)
  - [JavaScript Vs ECMAScript](#javascript-vs-ecmascript)
  - [Types of Script](#types-of-script)
  - [Prerequisites of using HTML and JavaScript](#prerequisites-of-using-html-and-javascript)
2. [JavaScript Getting Started](#javascript-getting-started)
  - [How to write Javascript?](#how-to-write-javascript)
  - [Where to write JavaScript in HTML?](#where-to-write-javascript-in-html)
  - [JavaScript Code structure](#javascript-code-structure)
  - [JavaScript Keywords](#javascript-keywords)
  - [Comments](#comments)
3. [JavaScript Language Fundamentals](#javascript-language-fundamentals)
  - [Generating Output](#generating-output)
4. [Variables](#variables)
  - [What is Variable?](#what-is-variable)
  - [Declaring variable without a value](#declaring-variable-without-a-value)
  - [Declaring multiple variables at once](#declaring-multiple-variables-at-once)
  - [Variable Naming Conventions](#variable-naming-conventions)
  - [Variable Scope](#variable-scope)
  - [The let and const keywords ES6](#the-let-and-const-keywords-es6)
5. [Data types](#data-types)
  - [Data types](#data-types)
  - [Primitive data type](#primitive-data-type)
  - [Non-primitive data type](#non-primitive-data-type)
  - [JavaScript has Dynamic Types](#javascript-has-dynamic-types)
  - [The typeof Operator](#the-typeof-operator)
  - [Type conversion](#type-conversion)
  - [Type coercion](#type-coercion)
6. [Operators](#operators)
  - [What is the Operator?](#what-is-the-operator)
  - [Arithmetic Operators](#arithmetic-operators)
  - [Assignment Operators](#assignment-operators)
  - [Logical Operators](#logical-operators)
  - [Relational Operators](#relational-operators)
  - [Conditional Operator](#conditional-operator)
  - [String Operators](#string-operators)
  - [Operator precedence](#operator-precedence)
7. [Functions](#functions)
  - [What is a Function?](#what-is-a-function)
  - [Types of Function](#types-of-function)
  - [Different ways to define Function](#different-ways-to-define-function)
  - [String Methods and Concatenation](#string-methods-and-concatenation)
  - [Template String](#template-string)
8. [Loops](#loops)
  - [The for loop](#the-for-loop)
  - [The while loop](#the-while-loop)
  - [The do while loop](#the-do-while-loop)
  - [The for in loop](#the-for-in-loop)
  - [The for of loop](#the-for-of-loop)
  - [Break and Continue statement](#break-and-continue-statement)
  - [for each loop](#for-each-loop)
9.  [Conditions](#conditions)
  - [The if statement](#the-if-statement)
  - [The if else statement](#the-if-else-statement)
  - [The if else if else statement](#the-if-else-if-else-statement)
  - [The switch case statement](#the-switch-case-statement)
10. [Array](#array)
  - [What is an Array?](#what-is-an-array)
  - [Create Array by array literal](#create-array-by-array-literal)
  - [Create Array by creating an instance of array directly](#create-array-by-creating-an-instance-of-array-directly)
  - [Create Array by using an array constructor](#create-array-by-using-an-array-constructor)
  - [Getting the Length of an Array](#getting-the-length-of-an-array)
  - [Accessing Looping through an Array Elements](#accessing-looping-through-an-array-elements)
  - [Adding Editing an Array Elements](#adding-editing-an-array-elements)
  - [Removing Deleting an Array Elements](#removing-deleting-an-array-elements)
  - [Array properties and methods](#array-properties-and-methods)
11. [Objects](#objects)
  - [Real Life Objects](#real-life-objects)
  - [What is an Object?](#what-is-an-object)
  - [Object literal](#object-literal)
  - [Creating an instance of Object directly](#creating-an-instance-of-object-directly)
  - [Object constructor](#object-constructor)
  - [Accessing objects properties](#accessing-objects-properties)
  - [Removing Deleting objects properties](#removing-deleting-objects-properties)
  - [Manipulating by Value Vs Reference](#manipulating-by-value-vs-reference)
  - [The Window object](#the-window-object)
  - [The Math Object](#the-math-object)
  - [Date and Time](#date-and-time)
12. [Events](#events)
  - [Understanding Events and Event Handlers](#understanding-events-and-event-handlers)
  - [Different Event category](#different-event-category)
  - [Different ways to write the event handler](#different-ways-to-write-the-event-handler)
13. [DOM (Document Object Model)](#dom-document-object-model)
  - [What is DOM?](#what-is-dom)
  - [Node](#node)
  - [JavaScript DOM Selectors](#javascript-dom-selectors)
  - [JavaScript DOM CSS Styling](#javascript-dom-css-styling)
  - [JavaScript DOM HTML get set attributes](#javascript-dom-html-get-set-attributes)
14. [What's the next step?](#whats-the-next-step)


## Introducing JavaScript

### Importance

At the beginning of my university life, I was talking about technology with one of my cousins. At one point in the talk, he said, "JavaScript is everything!" and that piqued my curiosity. Now I understand what he meant. The world would be scary without JavaScript. It is the most popular and powerful programming language in the world. Over the years since its inception, JavaScript has grown into a powerhouse. It is no longer only used by the web — it can now be found almost anywhere, including space. Why is that? For answers, we need to look at the amazing ecosystem that was built on it.

> **Syntax & Example**
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Intro HTML</title>

  <!-- Internal style -->
  <style>
    /* CSS selector: { property:value; } */
    body {
      font-family: Arial, sans-serif;
    }
  </style>

  <!-- Internal JavaScript in the head section -->
  <script>
    // Write all JavaScript code here
    alert("Welcome to JavaScript");
  </script>
</head>

<body>
  Content

  <!-- Internal JavaScript in the body section -->
  <script>
    // Write all JavaScript code here
    console.log("Welcome to JavaScript");
  </script>
</body>

</html>
```

### What is JavaScript?

- JavaScript is `1 of the 3 core languages/layers` of the web...(HTML, CSS & JavaScript).
- JavaScript is one of the most popular, widely used, lightweight scripting programming languages.
- JavaScript is an `Open Source`, `Cross-Platform`, and `Browser-based Client-Side (user computer)` programming language of the web.
- JavaScript is a dynamic computer programming language. It is an `interpreted (translated)` programming language with `object-oriented capabilities`.
- JavaScript is officially maintained by `ECMA (European Computer Manufacturers Association) as ECMAScript`.
- ECMAScript 6 (or `ES6` or ECMAScript 2015) is the latest major version of the ECMAScript standard.
- JavaScript is a case-sensitive language.

> [!TIP]\
Now-a-days with the help of `Node (Node.js)` JavaScript is used for `Back-end (Server-side)` API development. JavaScript is not compiled language, but it is a translated language (JavaScript Translator (embedded in the browser engine) is responsible for translating the JavaScript code for the web browser.

### What is a scripting language?

- A high-level programming language that is interpreted by another program at runtime rather than compiled by the computer's processor like other programming languages.
- A programming language designed for integrating and communicating with other programming languages.
  - Popular scripting languages are `JavaScript, VBScript, PHP, Perl, Python, Ruby, ASP`.
  - Since a scripting language is normally used in conjunction with another programming language, they are often found and used alongside `HTML, Java, or C++`.
- The simple difference between a scripting language and a programming language is that scripting languages do not require the compilation step and are instead interpreted.
  - A `C program` needs to be compiled before running, whereas normally, a scripting language like `JavaScript or PHP` does not need to be compiled.
- Scripting is an interpreted-based language, whereas Java, C, C++, and others are compiler-based languages.

#### What is a script?

- A script is nothing but sets of instructions
- Series of commands

### What can you do with JavaScript?

For a long time, JavaScript was used only as a `Client Side Front End Development language` to build browser-based interactive web pages. But currently, due to huge community support `(Node or Nide.js) JavaScript is a multi-purpose language` and is used to develop:
- Full-fledged Enterprise Web Applications
- Full-blown Mobile Apps
- Real-time Networking Apps (Chats, Audio/Video Streaming Services)
- Games
- Command Line Tools (CLI-Command Line Interface utilities)

#### JavaScript is used in billions of Web pages/web apps to add interactivity, validate forms and much more:

- JavaScript gives HTML designers a `programming tool`.
- JavaScript can react to `events` (mouse click, hover (rollover, rollout), focus, blur).
- JavaScript can be used to `validate` data (`Client-side validation`).
- JavaScript can manipulate `HTML content` and `CSS styles`.
- Dynamic `drop-down menus`, HTML contents at run time/on the fly.
- Displaying live/current/dynamic `date and time (clocks)`.
- Displaying `pop-up windows` and `dialog boxes` (an `alert`, `confirm`, and `prompt` dialog box).
- Change the website's `behavior` and make it more `dynamic with advanced` web designs.
- Perform and `control transitions` and `animations`.

#### However, there are more serious uses for javascript:

- **Browser Detection** - Detecting the browser used by a visitor.
- **Cookies** - Storing information on the visitor's computer.
- **Control Browsers** - Opening pages in customized windows.
- **Validate Forms** - Validating inputs to fields before submitting a form.

### Where does the JavaScript code run?

JavaScript was originally designed and developed to run only in browsers. But now, with the help of `Node.js` (a C++ program that includes Google's V8 JavaScript engine), we can build the back-end (server-side) for our web and mobile applications.

#### Common JavaScript Browser Engines

| Browser, Headless Browser, or Runtime | JavaScript Engine |
| ------------------------------------- | ----------------- |
| Mozilla                               | SpiderMonkey      |
| Safari                                | JavaScriptCore    |
| IE and Edge                           | Chakra            |
| Chrome                                | V8                |
| TrifleJS                              | V8                |
| Node.js                               | V8                |
| Io.js                                 | V8                |
| PhantomJS                             | JavaScriptCore    |
| HTMLUnit                              | Rhino             |

### Who are using JavaScript? 

- JavaScript is used by:
    - Front-end Developer
    - Back-end Developer
    - Full-stack Developer

- Big companies and brands build entire applications: 
    - Netflix
    - Walmart
    - PayPal
    - Microsoft
    - Facebook (React.js)
    - Google (Angular.js)
    - Ebay
    - Uber
    - Groupon

### History of JavaScript

- Invented by [“Brendan Eich”](https://en.wikipedia.org/wiki/Brendan_Eich) at `Netscape` in `1995`, originally named as `"LiveScript"`.
- `Netscape` and `Sun Java` agreed to rename `"LiveScript"` to `"JavaScript"` (as `Java` was already popular in the market).
- Not at all related to `Java` (completely different in concept and design).
- `Microsoft` developed a new version of "JavaScript" as `"JScript"` for `IE-3` in `1996`.
- JavaScript was submitted to `ECMAScript` in 1997.

### JavaScript Vs ECMAScript

| JavaScript                                  | ECMAScript                                  |
| ------------------------------------------- | ------------------------------------------- |
| JavaScript is a `scripting programming language`. | ECMAScript is a `specification/standard`. |
| JavaScript was invented by [“Brendan Eich”](https://en.wikipedia.org/wiki/Brendan_Eich) at `Netscape`. | ECMAScript standards are defined by `ECMA (European Computer Manufacturers Association)`. |
| JavaScript was released in 1995. | The first ECMAScript standard was published in 1997. |
| JavaScript uses/follows ECMAScript specifications/standards. | The ECMAScript specification defines many new features for JavaScript. |

### Types of Script

| Client-Side Scripting                     | Server-Side Scripting                     |
| ------------------------------------------|-------------------------------------------|
| Instructions for web Browser              | Instructions for web Server               |
| Client-side scripting is used when the user's browser already has all the code and the page is altered based on the user's input.     | Server-side scripting is used to create dynamic pages based on several conditions when the user's browser requests the server.       |
| Response from a client-side script is faster compared to a server-side script because the scripts are processed on the local computer. | Response from a server-side script is slower compared to a client-side script because the scripts are processed on the remote computer (server). |
| Client-side scripting languages such as JavaScript, VBScript, etc. are interpreted and executed by the web browser. | Server-side scripting languages such as ASP, PHP, Java, Python, Ruby, etc. run on the web server and the output is sent back to the web browser in HTML format. |
| **Example**: JavaScript, VBScript, ActionScript, HTML, XHTML, etc.  | **Example**: ASP, JSP, PHP, ASP.NET, Perl, Ruby, Python, CGI, etc. |


### Prerequisites of using HTML and JavaScript

### Tools for building web sites-web pages/writing HTML, CSS & JavaScript

1. **Text Editor/HTML Editor/Code Editor/Visual Code Editor** - `NotePad, NotePad++, SublimeText, Atom, Brackets, Coda, Visual Studio Code, DreamWeaver`, etc.
  - Just visit the registered website of any of your favorite editors, download and install it (like **Visual Studio Code** = https://code.visualstudio.com)
  - A JavaScript file (.js) is a text file itself consisting of JavaScript code/statements, so to create/modify a JavaScript file, we can use any text editors.

2. **Browsers - To view the output of .html pages with .js files** - `Google Chrome, Mozilla Firefox, Internet Explorer, Safari`, etc.
  - Once the .html/.htm file is created and saved, we can create a .js file and link it within HTML, and then we can see its output in any latest web browser.

3. **JavaScript Output / Debugging Tool (Developer console)** - 
  - alert() or window.alert()
  - console.log()
  - Google Chrome / Safari – `Developer Tools Inspect` / Inspect element (in the browser -> Right Click on the page -> choose `Inspect / Inspect Element -> Console Tab`)
  - Mozilla Firefox – `Firebug`

> [!TIP]\
Use the `F12` key on the keyboard to open the `developer tools`, then click on the `Console Tab`, or on an empty area in the browser page, right-click -> Inspect (Developer Tool) -> Console Tab. Here, you can write basic JavaScript statements and/or valid JavaScript code directly in the browser console panel/tab and get the output.

## JavaScript Getting Started

### How to write Javascript?

- The HTML `<script>.....</script>` tag is used to embed/insert/implement JavaScript programs/code into any part of an HTML document/page.
- The `<script>.....</script>` tag specifies that we are using JavaScript.
- The `<script>.....</script>` element can be placed in the `<head>` or `<body>` section of an HTML document.
- Each `<script>.....</script>` tag blocks the page rendering process until it has fully downloaded and executed the JavaScript code.
  - So the best practice is to place/add the `<script>.....</script>` at the bottom/end of the `body` tag/section, i.e., just before the closing `</body>` tag.

> [!TIP]\
JavaScript is the default scripting language in HTML. The old HTML standard attributes like `type="text/javascript"` and `language="javascript"` are no longer required in modern browsers.

> **Syntax & Example**
```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>03.01.js.script.tag.html</title>

  <!-- Internal styles -->
  <style>
    /* CSS selector: { property:value; } */
    body {
      font-family: Arial, sans-serif;
    }
  </style>

  <!-- Internal JavaScript in the head section -->
  <script>
    // Write all JavaScript code here
    alert("Welcome to JavaScript");
  </script>
</head>

<body>
  Content

  <!-- Internal JavaScript in the body section -->
  <script>
    // Write all JavaScript code here
    console.log("Welcome to JavaScript");
    document.write("This is dynamic content. Hello All, Let's write something on the web page");
  </script>
</body>
```

### Where to write JavaScript in HTML?

### JavaScript provides 3 places to write the JavaScript code in our webpage:

1. Inside the HEAD section
2. Inside the BODY section
3. External JavaScript .js file (separation of concerns)

#### Inside the HEAD section (code between the head tag)

- JavaScript programs/code/statements can be placed in the `<head>` section of an HTML page.
- However, each `<script>.....</script>` tag blocks the page rendering process until it has fully downloaded and executed the JavaScript code. Therefore, placing them in the `head` section of the document without any valid reason will significantly impact your website's performance.

> **Syntax & Example**
```html
<head>
  <!-- Internal JavaScript in the head section -->
  <script>
    // Write all JavaScript code here
    alert("Welcome to JavaScript written in head section");
  </script>
</head>
```

#### Inside the BODY section (code between the body tag)

- JavaScript programs/code/statements can be placed in the `<body>` section of an HTML page.
- Due to the blocking nature of the `<script>.....</script>` tag, it is ideal to place scripts at the end of the `body` section, just before the closing `</body>` tag. This will make your web pages load faster since it prevents obstructing the initial page rendering.

> **Syntax & Example**
```html
<body>
  <!-- Page content -->

  <!-- Internal JavaScript in the body section -->
  <script>
    // Write all JavaScript code here
    alert("Welcome to JavaScript written in body section");
    console.log("Welcome to JavaScript written in body section");
    document.write("<h2>Welcome to JavaScript written in body section</h2>");
  </script>
</body>
```

#### External JavaScript .js file (separation of concern)

- We can easily write JavaScript code between the `script` element. In a real-world application, we may have 100+ lines, or even 1000+ lines of code. Writing all that code inline here would not be ideal.
- It is important to extract and separate our JavaScript behavior code from our HTML markup code.
- A simple rule of thumb is that if we have a lot of JavaScript code, we should put it into a separate file.
- We can add an external JavaScript file by using the `<script>` tag with the `src` (source) attribute:
  - ```<script src="path/scriptfile.js"></script>```
  - We can provide a full URL (absolute path) or a relative path from the current page.
- By creating a single external JavaScript file, we can embed it in many HTML pages, which provides code reusability.

#### Advantages of External JavaScript 

- It separates HTML and JavaScript code (separation of concern)
- Code re-usability
- It makes HTML and JavaScript file/code easier to read, maintain and more meaningful/semantic
- Web page loads faster /increase the speed of the webpage (Cached JavaScript files)

> [!TIP]\
Usually, when an external JavaScript file is downloaded for the first time, it is stored in the browser's cache (like images and style sheets), so it won't need to be downloaded multiple times from the web server, which makes the web pages load faster/quickly.

> **Syntax & Example**
```html
<body>
  <!-- Page content -->

  <!-- Include external JavaScript in the body section -->
  <script src="./script.js"></script>
</body>
```
```js
// External js file
// Write all JavaScript code here
// Display an alert message
alert("Welcome to JavaScript written in external file");
// Log a message to the console
console.log("Welcome to JavaScript written in external file");
// Write HTML content to the document
document.write("<h2>Welcome to JavaScript written in external file</h2>");
```

### JavaScript Code structure

The syntax of JavaScript is the `set of rules` that define a correctly structured JavaScript program. Let's study some of the building blocks of JavaScript code:

#### JavaScript Statements

- One line of JavaScript code is one JavaScript statement/instruction/command.
- Statements are commands to the browser to do something/perform actions.
- A statement is a piece of code that expresses an action to take place.
- JavaScript code/program (or just JavaScript) is a sequence of statements.
- Statements are written between `<script>.....</script>` tags.
- Statements are separated by a semicolon (;), so we may write many statements in a line (optional).
- JavaScript ignores extra line breaks and white spaces.
- JavaScript is a case-sensitive language (VB, Pascal, HTML are case-insensitive).
- JavaScript is interpreted, not compiled (written and handed over to the web browser).
- All statements in JavaScript should be terminated by a semicolon (;).

> [!TIP]\
JavaScript statements are composed of **values, operators, expressions, keywords, and comments**.

#### Whitespace and Line Breaks

- JavaScript ignores `spaces, tabs, and newlines` that appear in JavaScript programs.
- We can freely use spaces, tabs, and newlines to format and indent programs in a neat, clean, and consistent way that makes the code easy to read and understand (not advisable).

#### Semicolons

- JavaScript statements are generally followed by a `semicolon` character.
- A semicolon may be omitted in `most cases` when a line break exists.
- JavaScript interprets the line break as an `implicit` semicolon, called an `automatic semicolon insertion`.
- **In most cases, a newline implies a semicolon. However, "in most cases" does not mean "always"!**

> [!TIP]\
It is a good programming practice to use semicolons; after every statement;

#### Case Sensitivity

- JavaScript is a case-sensitive language.
- In JavaScript, variables, language keywords, function names, and other identifiers must always be typed with consistent capitalization of letters.
- **Example**: `var firstName="Tahmid";` and `var FirstName="Tahmid";` Here, `firstName` and `FirstName` are different, i.e., two different variables.

> [!TIP]\
Take care and precautions when writing variable and function names in JavaScript.

#### JavaScript Code Blocks

- JavaScript commands/statements/code can be grouped together in code blocks, `inside curly brackets {...}`.
- Grouped statements/lines form code blocks.
- The purpose of code blocks is to define statements to be executed together, like a single JavaScript command.
- An often occurrence of a code block in JavaScript is a JavaScript `function`.

> **Syntax & Example**
```js
// External js file
// All JavaScript code is written here

// Define a function to display a welcome message
function sayHello() {
  alert("Hello All! Welcome to JavaScript!!");
}

// Define a function to calculate and display the total of two numbers
function showTotal() {
  var num1 = 10;
  var num2 = 20;
  var total = num1 + num2;
  alert("Total is: " + total);
}

// Invoke the sayHello function to display the welcome message
sayHello();

// Invoke the showTotal function to calculate and display the total
showTotal();
```

### JavaScript Keywords

Usually, JavaScript commands/statements start with a `specific keyword` which defines what `action/function` should the browser will perform/do:


| Keyword      | Keyword        | Keyword      | Keyword       | Keyword      |
| ------------ | -------------- | ------------ | ------------- | ------------ |
| break        | do ... while   | if ... else  | try ... catch | const        |
| continue     | for            | return       | var           | class        |
| debugger     | function       | switch       | let           | import       |


#### Reserved Keywords

JavaScript has several reserved keywords. These are the words that you cannot use as identifiers (variable names, function names, and loop labels) in your JavaScript programs. The following list shows the keywords that are reserved in `ECMAScript 6`. It also includes keywords that are `reserved for the future` as well as keywords that are `disallowed in strict mode`.
- **JavaScript keywords**: `arguments`, `await`, `break`, `case`, `catch`, `class`, `const`, `continue`, `debugger`, `default`, `delete`, `do`, `else`, `enum`, `eval`, `export`, `extends`, `false`, `finally`, `for`, `function`, `if`, `implements`, `import`, `in`, `instanceof`, `interface`, `let`, `new`, `null`, `package`, `private`, `protected`, `public`, `return`, `static`, `super`, `switch`, `this`, `throw`, `true`, `try`, `typeof`, `var`, `void`, `while`, `with`, `yield`.

### Comments

- Comments are a meaningful way to deliver the message (description to code) to others or for future reference, helping to understand and follow the code statements.
- Comments are special lines written for other developers as a reference, and the browser ignores them while interpreting.
- They are used to add information about the code, provide warnings or suggestions, and help end-users interpret the code by explaining the "why" and "how" of the code/program/logic.
- Comments are used to explain code, programs, and statements, making them more readable for developers.
- Comments are ignored by the JavaScript engine embedded in the browser.
- They can also be used to prevent the execution of certain logic when testing code.
- Comments can be placed anywhere in a script, as they don't affect its program execution since the engine simply ignores them.
- Comments help make the code easy to understand and avoid unnecessary code.

#### Types of JavaScript Comments

There are two types of comments in JavaScript:
1. Single-line Comments
2. Multi-line Comments

#### Single-line Comments

- Single-line JavaScript comments are used for one line of comment only.
- Single-line comments start with `two forward slashes`: **// is a single comment**.
- Any statements between `//` until the end of the line will be ignored by JavaScript (not be executed).
- Single-line comments do not need closure/closing.

> **Syntax & Example**
```javascript
// External js file
// Write all JavaScript code here

// Show alert box
alert("Welcome to JavaScript!");

var firstName = "Tahmid"; // variable to store firstName
var lastName = "Sarker"; // variable to store lastName
```

#### Multi-line Comments

- Multi-line comments usually comment out a block of code
- Multi-line comments in JavaScript can comment on bigger parts (a few lines) of code
- Multi-line comments are more convenient as it can be used to comment single as well as multi-line comments
- Multiline comments start with `forward slash and an asterisk, /* and also end with an asterisk and a forward slash */`:  /* multi-line comment */
- Multi-line comments need closing
- Multi-line comments are more often used for formal documentation.

> **Syntax & Example*
```js
/* Show alert box */
alert("Welcome to JavaScript!");

/* This is a multiline comment.
A code block can be commented on. */

/* var firstName = "Tahmid"; // variable to store firstName
var lastName = "Sarker"; // variable to store lastName */
```

## JavaScript Language Fundamentals

### Generating Output

- JavaScript does not have any `display or built-in print` functions.
- Many times, we may need to generate output from your JavaScript code, such as seeing the value of a variable or writing a message to the browser console to help you debug an issue in your running JavaScript code.
- That is why you have to use the JavaScript output function to generate output (browser window or browser console dialog boxes, writing output into an HTML element, etc.).
- Having knowledge of different output methods will help you debug or rewrite your code more conveniently.

#### Different ways to show output/display data

1. Writing into an alert box with `alert()` or `window.alert()`.
2. Writing into the browser console with `console.log()`.
3. Writing into the HTML/Browser Window with `document.write()`.
4. Writing into an element of HTML/Inserting Output Inside an HTML Element with `innerHTML`.

#### Displaying Output in Alert Dialog Boxes: alert() or window.alert()

- One can use `alert dialog boxes` to display messages or output data to the user.
- An alert dialog box is created using the `alert()` or `window.alert()` method.
- A small pop-up box appears with a close button to close the alert box.
- This method is great for short and rapid informative messages that can be instantly closed.

> **Syntax & Example**
```js
// External js file
// Write all JavaScript code here

alert("I am Md. Tahmid Sarker Mahi");
window.alert("I am learning JavaScript");
```

#### Writing Output to Browser Console: console.log()

- Programmers can easily output a message or write data to the browser console using the `console.log()` method.
- The `console.log()` function is mainly used for debugging code as it allows JavaScript output to be printed to the console.
- This is a simple, easy, but very powerful method for generating detailed output.

> **Syntax & Example**
```js
// External js file
// Write all JavaScript code here

console.log("I am Md. Tahmid Sarker Mahi");
console.log("I am learning JavaScript");
```

> [!TIP]\
Use `F12` key on the keyboard to open the `developer tools` then click on the `console tab`. You can write basic JavaScript statements directly in the browser console panel/tab and receive the output.

#### Writing Output into the HTML / Browser Window: document.write()

- The `document.write()` method is used to write content to the current document while the document is being parsed.
- Programmers use `document.write()` for testing purposes.

> **Syntax & Example**
```js
// External js file
// Write all JavaScript code here

document.write("I am Md. Tahmid Sarker Mahi");
document.write("I am learning JavaScript");
```

#### Inserting Output Inside an HTML Element: innerHTML

- We can write or insert output inside an HTML element using the element's `innerHTML` property.
- First, we need to select the element using a method such as `document.getElementById(id)`.

> [!TIP]\
HTML element manipulation is fully dependent on JavaScript DOM manipulation concepts.

> **Syntax & Example**
```js
// External js file
// Write all JavaScript code here

// Writing text string inside an element
document.getElementById("mainHeadingText").innerHTML = "Heading Text change dynamically on run-time";

var paraText = document.getElementById("mainParaText");
paraText.innerHTML = "<strong>This Paragraphic text inserted dynamically through innerHTML method.</strong>";
```

With JavaScript, we can do many cool and dynamic pieces of stuff (Image Gallery, Games, Forms), but for that one should be familiar with the core essentials/building blocks of the JavaScript programming language like Variables, Functions, Operators, Loops, Conditional Statements, Array, Objects, Events, DOM (Document Object Model), etc., which will be covered in the coming lessons.

## Variables

### What is Variable?

Variables are one of the most fundamental concepts in JavaScript and all other programming languages in the world.

- A variable is a `container to store/hold data/information`.
- Developers/Programmers use variables to `temporarily store/hold data/information` in computer memory.
- A variable is a kind of data holder where we can store a value for programming or calculation purposes.
- A JavaScript variable is simply a `name of the storage location (named containers/named storage)` for data.
- Variables are symbolic names for values.
- Variables are used to store data of different types like a string of text, numbers, boolean values like true/false, an array of data, etc.
- The data or value stored in variables can be set, updated, and retrieved whenever needed.
- Variables are declared using the `var` keyword.
- The `assignment operator (=)` is used to assign a value to a variable, like this: `var varName = value;` or `var firstName = 'JavaScript';`.
- By default, the value of a variable defined in JavaScript is `undefined` (variable is defined but value not assigned: `var firstName;` or `let lastName; console.log(firstName, lastName);` // undefined).

<hr/>

- **Example**: Variables are like `boxes or envelopes` that we use to `organize various kinds of stuff` and put a `label` on each box or envelope.
- **Example**: Variable declaration and assignment is just `like Maths & Algebra`: `x = 10`; and in JavaScript, we write `var x = 10;`.

<hr/>

> [!TIP]\
In ES6, the `'let'` and `'const'` keywords are used to declare variables.

> [!TIP]\
As a best practice of ES6, from now onwards variables must be defined with the `let` keyword: `let techName = 'JavaScript';`

<hr/>

> **Syntax & Example**
```js
// variables defined to hold different types of data
var techName = "JavaScript"; // String literal 
var version = 6; // Number literal
var isDone = true; // Boolean literal

console.log("Learning " + techName + version);
```

### Declaring variable without a value

Variables can also be declared without having any initial values assigned to them. This is useful for variables that are supposed to hold values like user inputs, calculations, status updates, etc.

> **Syntax & Example**
```js
// Declaring Variables
var techName;
var version;
var isDone;

// Assigning value
techName = "JavaScript";
version = 6;
isDone = true;

console.log("Learning " + techName + version);

// ------------------------------

// Declaring Variable
var userName;

// Assigning value
userName = "Tahmid";

console.log("Welcome " + userName);
```

### Declaring multiple variables at once

We can also `declare multiple variables` and set their initial values in a single statement, with each variable `separated by a comma`.

> **Syntax & Example**
```js
// Declaring multiple variables
var techName = "JavaScript", version = 6, isDone = true;

// Declaring multiple variables in multiple lines for readability
var techName = "JavaScript", 
    version = 6, 
    isDone = true;

console.log("Learning " + techName + version);

// ------------------------------

// Declaring multiple variables
var firstName = "Tahmid", lastName = "Sarker", age = 25, isMarried = true;

// Declaring multiple variables in multiple lines for readability
/* var firstName = "Tahmid", 
   lastName = "Sarker", 
   age = 25, 
   isMarried = true; */

console.log("I am " + firstName + " " + lastName);
```

### Variable Naming Conventions

All JavaScript variables must be `identified`, referred, defined, or named with `unique names`, called as `identifiers`. The naming rules in JavaScript are not much different from any other programming language. 

- There are some rules for declaring/naming a JavaScript variable (also known as `identifiers`):
  - Identifiers are `simply names` in JavaScript.
  - Identifiers are used to name variables, keywords, functions, and labels.
  - Identifiers can be `short names/nicknames` (like name, age, num1, isDone, sum) or more descriptive names (firstName, totalDashboards, isSeniorCitizen).

**The basic rules for defining/assigning names for variables (unique identifiers) are:**

- A variable name must start with a letter, underscore (_), or dollar sign ($).
  - **Example**: var firstName, var _firstName, var $firstName;
- Names can contain letters, digits, underscores, and dollar signs.
  - **Example**: var $num_total1; 
- A variable name cannot start with a number or special characters.
  - **Example**: var 1num_total, var .num_total;
- A variable name cannot contain spaces.
  - **Example**: var num_total;
- Variable names are case sensitive.
  - **Example**: var firstName='Tahmid'; and var FirstName='Tahmid'; here `firstName` and `FirstName` are different, i.e., two different variables.
- A variable name cannot be a JavaScript keyword or a JavaScript reserved word.
   - **Example**: var var; var switch; var for; var true;
- One should always give meaningful/descriptive names to variables.
- For naming variables that contain multiple words, the `camelCase` method is commonly used (camelCase is the default method for identifier naming).

> [!TIP]\
In the programming world, there are two most popular methods/mechanism of writing multiple words identifiers: (Underscore, Camel Case)

1. **Underscore**: first_name, last_name, date_of_birth, is_passed, native_place
2. **Camel Case:**: firstName, lastName, dateOfBirth, isPassed, nativePlace  OR <br/> : FirstName, LastName, DateOfBirth, IsPassed, NativePlace 

> **Syntax & Example**
```js
// variables defined to hold different types of data
var _firstName = "JavaScript";
var $version = 6;
var $num_total1 = 10;

window.alert("variables details: " +  _firstName + " " + $version + " " + $num_total1);

// wrong identifiers
// var #name;
```

### Variable Scope

The scope of a variable is the region/coverage of your program in which it is defined and exist/available. JavaScript variables have two scopes:
1. Local Variables
2. Global Variables

#### Local Variables

- A JavaScript local variable is declared `inside a block or function`.
- It is accessible within the `function or blocks only`.
- A local variable will be `visible only within a function` where it is defined.
- `Function parameters` are always local to that function.

> [!TIP]\
In the function body, a `local variable takes precedence` over a global variable with the same name.

> **Syntax & Example**
```js
// global variable
var globalName = "Global";

window.alert(globalName);

function showName() {
  // local variable
  var localName = "Local";

  window.alert(localName);
  window.alert(globalName); // recall global variable
}

// invoke/call/run function
showName();

// error - as local variable not exist/available outside of block { }
window.alert(localName);
```

#### Global Variables

- A variable `declared outside the function/at the root` or declared `with the window object` is known as a global variable.
- A JavaScript global variable is accessible from any function.
- A global variable has a global scope, which means it can be defined and accessed anywhere in JavaScript code/program.

> **Syntax & Example**
```js
// global variable
var globalName = "Global";

window.alert(globalName);

function showName() {
  // local variable
  var globalName = "Local";

  window.alert(globalName);

  // define global variable with window
  window.globalVersion = 29;
  window.alert("global variable from inside function: " + window.globalVersion);
}

// invoke/call/run function
showName();

// access global variable defined inside function
window.alert("global variable from outside function: " + window.globalVersion);
```

### The let and const keywords ES6

ES6 introduces two new keywords `let` and `const` for declaring variables. The `var`, `let`, and `const` keywords are almost the same, with just a few differences in scope.

- In older programs, `var` is used a lot, which declares a variable as function-scoped, but in a slightly different, outdated way, with scope issues.
- Both `let` and `const` keywords declare variables scoped at the block level ({}).
- Block scoping means that a new scope is created between a pair of curly brackets {}.

#### The let Keyword

`ES6` introduces the new `let` keyword for declaring variables. Prior to ES6, the only way to declare a variable in JavaScript was with the `var` keyword. Let's see what the difference is:
- Variables declared with the `var` keyword are `function-scoped` and can be `hoisted` to the top within their scope.
- Variables declared with the `let` keyword are `block-scoped ({})` and they are not hoisted.

> **Syntax & Example**
```js
// traditional var syntax
var techName1 = "JavaScript";

for (var i = 1; i <= 5; i++) {
  console.log("i : " + i); // 1,2,3,4,5
  console.log("inside block:" + techName1);
  var version1 = 100;
}
console.log("outside: " + i); 
console.log("outside: " + version1); 

// ------------------------------

// ES6 syntax
let techName2 = "LiveScript";

for (let n = 1; n <= 5; n++) {
  console.log("n : " + n); // 1,2,3,4,5
  console.log("inside block:" + techName2);
  let version2 = 100;
}

console.log(n); // ReferenceError: n is not defined
console.log("outside: " + version2);  // ReferenceError: version2 is not defined
```

#### The const Keyword

`ES6` introduces the new `const` keyword for declaring variables. 
- Use `const` to declare a constant `(read-only / unchanging)` variable
- Constants are `read-only`, you `cannot reassign new values` to them
- In Program/logic when the variable will never change, they can be declared as `const`
- constants are named using capital letters and underscore **Example**: const NATIVE_CITY
- `const` are also `block-scoped` like `let`
- However, you can change `object properties` or `array elements`

> **Syntax & Example**
```js
// Traditional var syntax
var PI1 = 3.14;
console.log(PI1); // 3.14

PI1 = 100;
console.log(PI1); // 100

// ------------------------------

// ES6 syntax
const PI2 = 6.28;
console.log("ES6 syntax const: " + PI2); // 6.28

// Trying to reassign a value to a constant will result in an error
// PI2 = 100; // This line would cause an error
```

## Data types

### Data types

A variable in JavaScript can contain `any type of data`. Data types specify what `kind of data` can be stored and manipulated within the variable in a program. In JavaScript, different data types are available to hold different types of values/data. There are `two main categories/types` of data types in JavaScript:
1. Primitive (Primary or Value) data types
  - String
  - Number
  - Boolean
  - Undefined
  - Null
  - Symbol (newly introduced in ES6)
2. Non-primitive (Reference or Composite) data types
  - Array
  - Object
  - Function

### Primitive data type

Primitive data types can `hold only one value at a time.` Primitives are `compared by value`. Two values are strictly equal if they have the same value.

There are different types of primitive data types in JavaScript. They are as follows:

| Data Type   | Description                                               |
| ----------- | --------------------------------------------------------- |
| String      | Represents textual data, e.g. "welcome" or 'to JavaScript' |
| Number      | Represents numeric values, e.g. 10, 100.29                 |
| Boolean     | Represents a boolean value, either false or true           |
| Undefined   | Represents an undefined value (a variable declared but not assigned a value) |
| Null        | Represents null, i.e. no value at all                      |

#### String

- The string data type is used to `represent textual data (i.e. sequences of characters)`.
- Strings hold information in `words/text`.
- A string in JavaScript must be surrounded by `"double"` or `'single'` quotes.

> **Example**
```js
var firstName = "Java"; 
var lastName = 'Script';
```

#### Number

- The number data type is simply defined without quotes and is used to represent positive or negative numbers with or without a decimal place.
- Many mathematical operations can be done on numbers, such as multiplication (*), division (/), addition (+), subtraction, and so on.

> **Example** 
```js
var age = 25; 
var id = 1;
```

#### Boolean

- The Boolean data type can hold only two values: `true` or `false`.
- `true` represents ON / yes / correct / 1, while `false` represents OFF / no / incorrect / 0.
- Boolean data types are often used in `conditional testing` of code.

> **Example** 
```js
var isDone = true; 
var isMarried = false;
```

#### Undefined

- The meaning of undefined is `“value is not assigned”`
- The undefined data type can only have one value-the special value undefined
- A variable has been declared, but `not been assigned a value`
- A variable `without a value`, The type is also undefined

> **Example** 
```js
var firstName;
var country;
```

#### Null

- A null value means that there is no value.
- It is a special value that represents "nothing", "empty", or "value unknown".
- It is not equivalent to an empty string ('' or ' ', "", " "); it is simply nothing.

> **Example**
```js
var firstName = null;
var id = null;
```

### Non-primitive data type

- Non-primitive/Reference data types can hold `collections of values and more complex entities`.
- Non-primitive values are compared by `reference` instead of value.
- Data does not store in the variables but is stored on the heap - a dynamically allocated memory reference.
- It's a pointer to a location in memory, accessed by reference.

There are different types of non-primitive data types in JavaScript. They are as follows:

| Data Type  | Description                                                           |
|------------|-----------------------------------------------------------------------|
| Array      | Represents a group of similar values (multiple values in one variable) |
| Object     | Represents an instance through which we can access members (properties and values) |
| Function   | Represents a function (a block of code to execute)                     |

### JavaScript has Dynamic Types

We have two types of programming languages:
1. Static languages
  - Declare a variable, the type of the variable is set and it cannot be changed in the future.
2. Dynamic languages
  - Variables can change at runtime. One variable can store different types of values as per requirements. We can assign any value at any time based on logic and requirements.

- A JavaScript `variable can contain/hold any data ie. any type of data`, A variable can hold any type of data, such as numbers, strings, or booleans, at different moments.
- It simply means that `same variable can be used to hold different data types`
- JavaScript is a dynamic type language, means you don't need to specify a type of the variable because it is dynamically used by JavaScript engine

> **Syntax & Example**
```javascript
let name = "JavaScript";
name = false;
name = 100;

alert(name);
alert(typeof(name));
```

### The typeof Operator

- The typeof operator returns the `type of the argument`.
- It’s useful when you want to process values of different types differently or when you want to perform a quick data type check.
- The typeof operator can be used to find out what `type of data a variable` or operand contains.
- It can be used with or without parentheses `(typeof x)` or `typeof x)`.

> **Syntax & Example**
```js
// use typeof to find data type of variables

// Strings
alert(typeof "Hello"); // "string"
alert(typeof '12'); // "string"

// Numbers
console.log(typeof(100)); // "number"
console.log(typeof(100.29)); // "number"

// Booleans
alert(typeof true); // "boolean"
alert(typeof(1 == 2)); // "boolean"

// Undefined
console.log(typeof undefined); // "undefined"

var init;
console.log("type of init: " + typeof init); // "undefined"

// Null
console.log(typeof null); // "object"
var initObject = null;
console.log("type of initObject: " + typeof initObject);  // "object"

// Objects
alert(typeof {name: "Tahmid", age: 25}); // "object"
alert(typeof document); // "object"
alert(typeof window); // "object"

// Arrays
var techArray = [];
console.log("type of techArray: " + typeof techArray);  // "object"
console.log(typeof ["JavaScript", "jQuery", "Angular"]);  // "object"
console.log(typeof ["Tahmid", 25, "Bangladesh"]);  // "object"

// Functions
console.log(typeof function(){}); // "function"
console.log(typeof alert); // "function"
console.log(typeof window.alert); // "function"

// Symbol
alert(typeof Symbol("dob")); // "symbol"
```

### Type conversion

- Type conversion is nothing but taking a variable and changing its data type as per the needs, requirements, and logic.
- In JavaScript, when we take an `input in the form, its data type is a string by default`, so for any calculations, we need to `parse` it to an `integer/int` or a `number`.
- Data type conversion can be either implicit (automatic) or explicit (forced/manually).

> **Syntax & Example**
```js
// Number to String conversion
let num1 = 100;

console.log(num1); // 100
console.log(typeof num1); // "number"

num1 = String(num1);

console.log(num1); // "100"
console.log(typeof num1); // "string"
console.log(num1.length); // 3

// Boolean to String conversion
let boolValue1 = String(false);

console.log(boolValue1); // "false"
console.log(typeof boolValue1); // "string"

// Date to String conversion
let curDate = String(new Date());

console.log(curDate); // Current date and time as a string
console.log(typeof curDate); // "string"

// Array to String conversion
let numArray = String([1,2,3,4,5]);

console.log(numArray); // "1,2,3,4,5"
console.log(typeof numArray); // "string"

// toString() method
let curString1 = (1000).toString();
let curString2 = (true).toString();

// String to Number conversion
let num2 = "100";

console.log(num2); // "100"
console.log(typeof num2); // "string"
// console.log(num2.toFixed(2)); // Error: String type variables do not have any properties or methods related to numbers

num2 = Number(num2);

console.log(num2); // 100
console.log(typeof num2); // "number"
console.log(num2.toFixed(2)); // "100.00"

// Boolean to Number conversion
let boolValue2 = Number(false);

// parseInt() and parseFloat() methods
let curNumber1 = parseInt("100");
let curNumber2 = parseFloat("100.41");
```

### Type coercion

- Type coercion simply refers to JavaScript's ability to automatically convert types (developers do not do it, but JavaScript does it for us).
- Type coercion is the process of converting a value from one type to another (such as string to a number, object to boolean, and so on).
- The JavaScript engine converts the type according to its rules (implicit, i.e., automatic conversion of data types).

> **Syntax & Example**
```js
const num1 = '20'; // Corrected
const num2 = 10;   // Define num2

const sum = Number(num1) + num2; // Convert num1 to a number using Number() function
console.log(sum);                 // Output: 30
console.log(typeof sum);          // Output: number
```

## Operators

### What is the Operator?

- We know/use many operators since our initial school days, such as addition (+), multiplication (*), subtraction (-), and parentheses ().
- Operators are symbols/keywords that tell the JavaScript engine to perform some sort of action.
- JavaScript operators are symbols that are used to perform operations on operands.
- Operators are used along with variables and constants to create expressions and implement logic and algorithms.

> [!TIP]\
Let us take a simple expression `var sum = 1 + 2`:
- Here, 1 and 2 are called `operands`, and 
- `=` and `+` are called the `operators`.
- `=` is the assignment operator, and `+` is the arithmetic operator.

> **Syntax & Example**
```js
// Lets take a look on simple expression 
var sum = 1 + 2;

// Here 1 and 2 are called `operands` and 
// `=` & `+` are called the `operator`
// `= is the assignment` operator, `+ is the arithmetic` operator
```

**JavaScript supports the following types of operators**:
1. Arithmetic Operators
2. Assignment Operators
3. Logical Operators
4. Comparison (or Relational) Operators
5. Conditional (or ternary) Operators
6. String Operators
7. Bitwise Operators

### Arithmetic Operators

- Arithmetic operators are used to perform arithmetic operations (just like mathematics - calculations) on numbers/the operands

JavaScript supports the following Arithmetic operators (List of Arithmetic operators):

| Operators | Description                           | Example / Result                                |
| --------- | ------------------------------------- | ----------------------------------------------- |
| +         | Addition                              | `x + y` (Sum of x and y)                        |
| -         | Subtraction                           | `x - y` (Difference between x and y)            |
| *         | Multiplication                        | `x * y` (Product of x and y)                     |
| /         | Division                              | `x / y` (Quotient of x and y)                    |
| %         | Modulus (Division Remainder)          | `x % y` (Remainder of x divided by y)            |
| ++        | Increment                             | `x++` (Post-increment) or `++x` (Pre-increment)   |
| --        | Decrement                             | `x--` (Post-decrement) or `--x` (Pre-decrement)   |
| **        | Exponentiation (ES2016 / ES6)         | `x ** y` (Multiply x by y times)                 |

> **Example**
```js
// Arithmetic operators

var num1 = 10;
var num2 = 4;

// Addition
alert("Addition: " + (num1 + num2)); // 14
// Subtraction
alert("Subtraction: " + (num1 - num2)); // 6
// Multiplication
alert("Multiplication: " + (num1 * num2)); // 40
// Division
alert("Division: " + (num1 / num2)); // 2.5
// Modulus (Remainder)
alert("Modulus (Reminder): " + (num1 % num2)); // 2
// Increment
num1++;
alert("After Increment: " + num1); // 11
// Decrement
num2--;
alert("After Decrement: " + num2); // 3
// Exponentiation
alert("Exponentiation: " + (num1 ** num2)); // (10 ** 4) = 10 * 10 * 10 * 10 = 10000
```

### Assignment Operators

- The Assignment operators are used to assign specific values to variables.

JavaScript supports the following Assignment operators (List of Assignment operators):

| Operator | Description          | Example / Result                                        |
| -------- | -------------------- | ------------------------------------------------------ |
| =        | Assignment           | `total = x + y;` (assigns a value to the variable) |
| +=       | Add and assign       | `x += y` (adds a value to the variable) |
| -=       | Subtract and assign  | `x -= y` (subtracts a value from the variable) |
| *=       | Multiply and assign  | `x *= y` (multiplies a value to the variable) |
| /=       | Divide and assign    | `x /= y` (divides a value from the variable) |
| %=       | Modulus and assign   | `x %= y` (calculates the modulus value of the variable) |

> **Example**
```js
// Assignment operators

var num1 = 10;
var num2 = 20;

// Old methodology
num1 = num1 + num2;
console.log(num1); // 30

// New techniques
num1 += num2;
console.log(num1); // 30

num2 -= num1;
console.log(num2); // -10

num1 *= num2;
console.log(num1); // -300

num2 /= num1;
console.log(num2); // 0

num1 %= num2;
console.log(num1); // NaN (Not a Number) because dividing by zero results in NaN
```

### Logical Operators

- The Logical operators are used to make decisions based on multiple conditions.
- The logical operators are typically used to combine multiple conditional statements and evaluate them.

JavaScript supports the following Logical operators (List of Logical operators):

| Operators   | Description                           | Example / Result                                      |
| ----------- | ------------------------------------- | ----------------------------------------------------- |
| &&          | Logical AND                           | `x && y` (True if both operands, x and y, are true) |
| &#124;&#124; | Logical OR                            | `x &#124;&#124; y` (True if either x or y is true) |
| !           | Logical NOT                           | `!x` (True if x is not true)                        |

> **Syntax & Example**
```js
// Logical operators - basic examples

// && (Logical AND) - returns true if both operands are true
console.log("true && true: ", true && true); // true
console.log("true && false: ", true && false); // false
console.log("false && true: ", false && true); // false

// ------------------------------

// || (Logical OR) - returns true if one of the operands is true
console.log("true || true: ", true || true); // true
console.log("true || false: ", true || false); // true
console.log("false || true: ", false || true); // true

// ------------------------------

// ! (Logical NOT) - True if operand is not true (i.e., true if the other is false)
var isSeniorCitizen = true;

var isYoungGeneration = !isSeniorCitizen;
console.log("isYoungGeneration: ", isYoungGeneration); // false
```
<hr/>

> **Syntax & Example**
```js
// Logical operators - real world scenario/example

// Determine credit/loan eligibility
var isEarningHighIncome = true; // Applicant has a high income
var isGoodCibilScore = false;   // Applicant has a poor credit score
var isEligibleForLoan;

// Check eligibility using && (Logical AND) operator
isEligibleForLoan = isEarningHighIncome && isGoodCibilScore;
alert("isEligibleForLoan: " + isEligibleForLoan);

// Check eligibility using || (Logical OR) operator
isEligibleForLoan = isEarningHighIncome || isGoodCibilScore;
alert("isEligibleForLoan: " + isEligibleForLoan);

// Determine if the loan is refused using ! (Logical NOT) operator
var isLoanRefused = !isEligibleForLoan;
alert("isLoanRefused: " + isLoanRefused);
```

### Relational Operators

- The JavaScript comparison operator compares the two operands.
- It compares two values in a Boolean fashion.
- The comparison operators are used to determine the similarity and difference between different variables.

JavaScript supports the following Comparison (or Relational) operators (List of Comparison (or Relational) operators):

| Operators | Description                           | Example / Result                      |
| ----------|---------------------------------------|---------------------------------------|
| ==        | Loose Equality Operator               | `x == y`    (True if x is equal to y)     |
| ===       | Strict Equality Operator              | `x === y` (True if x is equal to y, and they are of the same type) |
| !=        | Not equal to                          | `x != y` (True if x is not equal to y)           |
| !==       | Not identical                         | `x !== y` (True if x is not equal to y, or they are not of the same type) |
| <         | Less than                             | `x < y` (True if x is less than y)|
| >         | Greater than                          | `x > y`    (True if x is greater than y)|
| <=        | Less than or equal to                 | `x <= y` (True if x is less than or equal to y) |
| >=        | Greater than or equal to              | `x >= y` (True if x is greater than or equal to y)|

> **Syntax & Example**
```js
// Comparison (or Relational) operators
var num1 = 25;
var num2 = 35;
var num3 = "25";

// Loose equality check (value only)
alert(num1 == num3);  // true
// Strict equality check (value and type)
alert(num1 === num3); // false
// Inequality check (value only)
alert(num1 != num2);  // true
// Strict inequality check (value and type)
alert(num1 !== num3); // true
// Less than check
alert(num1 < num2);   // true
// Greater than check
alert(num1 > num2);   // false
// Less than or equal to check
alert(num1 <= num2);  // true
// Greater than or equal to check
alert(num1 >= num2);  // false
```

### Conditional Operator

- The Conditional Operator returns a value based on the condition, similar to an if-else statement.
- The conditional (ternary) operator is the only JavaScript operator that takes three operands.
- The conditional operator assigns a value to a variable based on a condition.
- This operator is often used as a shortcut or shorthand method for the if statement.
- **Syntax**: variablename = (condition) ? TRUE value: FALSE value 

| Operators | Description                           | Example / Result                      |
| ----------|---------------------------------------|---------------------------------------|
| ?         | Ternary operator                      | var result = x < y ? 'x is smaller' : 'y is smaller' (short hand method to write if condition)  |

> **Syntax & Example**
```js
// Conditional (? or ternary) Operator

// Age category determination
var currentAge = 100;
var category;

category = (currentAge < 18) ? "Minor" : "Major";
alert("AGE category: " + category);

// Fees determination based on membership status
var isAuthorisedMember = true;
var fees;

fees = (isAuthorisedMember == true) ? 5 : 10;
alert("fees / charges: " + fees);
```

### String Operators

Variables can also have string values. The `+` operator can be used to concatenate strings as well as numbers.

There are two operators which can also be used be for strings:

| Operators | Description                           | Example / Result                      |
| ----------|---------------------------------------|---------------------------------------|
| +         | Concatenation                         | `string1 + string2` (Concatenation of `string1` and `string2`) |
| +=        | Concatenation assignment              | `string1 += string2` (Appends `string2` to `string1`) |

> **Syntax & Example**
```js
// String Operators
var message1 = "Hello";
var message2 = " World!";
 
alert(message1 + message2); // Outputs: Hello World!
 
message1 += message2;
alert(message1); // Outputs: Hello World!
```

### Bitwise Operators

Bitwise operators are used to perform bitwise operations on operands. The operands are converted to 32-bit integers and expressed by a series of bits (binary numbers).

JavaScript supports the following Bitwise operators (List of Bitwise operators):

| Operators | Description                           | Example / Result                      |
| ----------|---------------------------------------|---------------------------------------|
| &         | AND                                   | `x & y` (Bitwise AND of x and y) |
| &#124;     | OR                                    | `x &#124; y` (Bitwise OR of x and y) |
| ~         | NOT                                   | `~x` (Bitwise NOT of x) |
| ^         | XOR                                   | `x ^ y` (Bitwise XOR of x and y) |
| <<        | Left shift                            | `x << y` (Shift x y bits to the left) |
| >>        | Right shift                           | `x >> y` (Shift x y bits to the right) |
| >>>       | Zero fill right shift                 | `x >>> y` (Shift x y bits to the right, fill with zeros) |

> **Syntax & Example**
```js
// Bitwise Operators
var num1 = 5; // Binary: 101
var num2 = 3; // Binary: 011

alert("Bitwise AND: " + (num1 & num2)); // Result: 1 (Binary: 001)
alert("Bitwise OR: " + (num1 | num2)); // Result: 7 (Binary: 111)
alert("Bitwise NOT: " + (~num1)); // Result: -6 (Binary: 11111111111111111111111111111010)
alert("Bitwise XOR: " + (num1 ^ num2)); // Result: 6 (Binary: 110)
alert("Left shift: " + (num1 << num2)); // Result: 40 (Binary: 101000)
alert("Right shift: " + (num1 >> num2)); // Result: 0 (Binary: 0)
alert("Zero fill right shift: " + (num1 >>> num2)); // Result: 0 (Binary: 0)
```

### Operator precedence

- If an expression has more than one operator, the `execution order is defined by their precedence`, or the implicit priority order of operators.
- Operator precedence determines/describes the way in which operators are parsed with respect to each other / `order in which the operations are performed`.
- The operations inside the `parentheses ()` are computed first.
- If many operations have the same precedence (like addition and subtraction), they are `computed from left to right`.

> **Syntax & Example**
```js
// Operator precedence
var result1 = 10 + 2 * 5;
alert("10 + 2 * 5 =  " + result1); // The answer is 20 NOT 60 (12 * 5 ), actually * or multiplication has higher precedence so the actual calculation is like 10 + (2 * 5) = 10 + 10 = 20

// Changing precedence with parentheses ()
var result2 = (10 + 2) * 5;
alert("(10 + 2) * 5 =  " + result2); // (12) * 5 = 60

// Same precedence operators
var result3 = 10 + 5 - 2;
alert("10 + 5 - 2 =  " + result3); // 13, first addition then subtraction

var result4 = 10 + (5 - 2);
alert("10 + (5 - 2) =  " + result4); // 13, first subtraction ( ) than addition
```

## Functions

### What is a Function?

- A function is basically a `group of statements that perform specific tasks/operations`.
- Functions provide a way to `create reusable code packages` which are more portable and easier to debug.
- Functions allow a programmer to `divide a big program` into several small and manageable functions.
- It helps programmers in writing `modular code`.
- A function is a kind of reusable tool where we can write code/functionality to reuse whenever we want (Functions allow the code to be called many times without repetition).
- Wrapping up/making smaller chunks of statements/reusable code together for readability or separation of concern/proper organization is functions – (Grouping of a repetitive task).
- Functions (logical block of code) are one of the most important control structures in any programming language.
- In other languages, it might be called `modules` or `subroutines`.
- There are two steps to utilize a function: 
  1. Create/define a function with the `function` keyword.  
  2. Call/invoke a function.

> [!TIP]\
Best Practice - First Define function than call/invoke it!

#### Here are some advantages of using functions:

- **Code reusability** - call a function several times
- **Less coding** - makes our program compact, no need to write lines of code each time
- **Easier to maintain** - changes are done only at one location
- **Easier to eliminate the errors** - fixing errors becomes much easier

#### Function Definition / Function Declaration / Creating Function

- The function declaration starts by using the `function` keyword, 
- followed by a `unique function name`, 
- a list of `parameters in parentheses` (that might be empty), 
- and a statement block surrounded by `curly braces { }`.

> **Syntax & Example**
```javascript
// 1. Define / declare / create function
function showMessage() {
  // Body of function 
  // Code to be executed
  console.log("welcome to JavaScript function");
  alert("welcome to JavaScript function");    
}
```

#### Function Invocation / Calling a Function / Run a Function

- A defined function can be invoked/called/run from anywhere in the document by typing the function name followed by a set of parentheses, like functionName().

> **Syntax & Example**
```js
// 2. Invoke / call the function
showMessage();
```

#### Function Naming

Function `denotes an action/task`. The function name should be `brief, as accurate as possible and describe` what the function does, like a `verb`.

Usually, Function name starts with:

- "getSomething" – returns a value.
- "createSomething" – creates something.
- "calcSomething" – calculates something.
- "checkSomething" – checks something and returns a boolean, etc.

Examples of function names:
- getSum();
- createFields();
- calcAge();
- checkUserType();

### Types of Function

- Regular Function
- Parameterized Function
- Return Type Function (Function returning values)

#### Regular Function

- Simple/Normal function which we use daily to perform some action/task

> **Syntax & Example**
```js
var name = "Tahmid";

// 1. Define / declare / create function
function sayHello() {
  // Body of function 
  // Code to be executed
  console.log("Hello " + name);
  alert("Hello " + name);    
}

// 2. Invoke / call the function
sayHello();
```

#### Parameterized Function

- One can pass data to functions using parameters (function arguments).
- You can specify parameters when you define your function to accept input values at runtime.

> **Syntax & Example**
```js
// Parameterized function
// 1. Define / declare / create function
function sayHello(name) {
  // Body of function 
  // Code to be executed
  console.log("Hello " + name);
  alert("Hello " + name);    
}

// 2. Invoke / call the function
sayHello("Tahmid");

sayHello("Sarker");

// ------------------------------

var total;

function calculateSum(num1, num2) {
  // Calculate the sum of two numbers
  total = num1 + num2;
  console.log(total);
}

// Calculate sum of numbers
calculateSum(10, 20);
calculateSum(100, 200);
```

#### Default Values for Function Parameters ES6

With ES6, now you can specify default values to the function parameters. This means that if no arguments are provided to the function when it is called these default parameters values will be used.

> **Syntax & Example**
```js
// Parameterized function with default parameters

// 1. Define / declare / create function
function sayHello(name = "User") {
  // Body of function 
  // Code to be executed
  console.log("Hello " + name);
  alert("Hello " + name);    
}

// 2. Invoke / call the function
sayHello();

sayHello("Tahmid");

// ------------------------------

var total;

function calculateSum(num1 = 1, num2 = 2) {
  total = num1 + num2;
  console.log(total);
}

// Calculate sum of numbers
calculateSum();
calculateSum(100, 200);
```

#### Return Type Function (Function returning values)

- A function can `return a value` back to the script that called the `function, as a result, using the return statement`.
- We can call a function that returns a value and use it in our program.
- The return statement is usually placed as the last line of the function.

> **Syntax & Example**
```js
// Return type function
// 1. Define / declare / create function
function getSum(num1, num2) {
  // Body of function 
  // Code to be executed
  var sum = num1 + num2;
  return sum;
}

// 2. Invoke / call the function
console.log(getSum(10, 20));
console.log(getSum(100, 200));

var total = getSum(50, 50);
alert(total);
```

### Different ways to define Function

The syntax that we've used before to create functions is called `function declaration`. There is another syntax for creating a function that is called a `function expression` and `Immediately Invoked Function Expression (IIFE)`.

#### function declaration (Regular/Normal function)

#### function expression

- Variables contain the expressions of a function.
  - Anonymous function expression.
  - Named function expression.

> **Syntax & Example**
```js
// Function declaration (Regular / normal function)
function getSum1(num1, num2) {
  var total = num1 + num2;
  return total;
}

// Function expression - Anonymous
var getSum2 = function(num1, num2) {
  var total = num1 + num2;
  return total;
};

alert(getSum2(10, 20));

// Assign function to another variable
var sum1 = getSum2;
alert(sum1(100, 200));
```

> **Syntax & Example**: 
```js
// Function expression - named
var getSum2 = function getTotal(num1, num2) {
  var total = num1 + num2;
  return total;
};

alert(getSum2(10, 20));

// Assign function to another variable
var sum1 = getSum2;
alert(sum1(5, 10));
```

#### Immediately invoked function expression (IIFE)

- It runs as soon as the browser finds it.
- Declare and run the function at the same time.

> **Syntax & Example**
```js
// Immediately invoked function expression (IIFE)
(function () {
  console.log("Welcome to Immediately invoked function expression (IIFE)");
})();

(function(userName) {
  console.log("Welcome", userName);
})("Tahmid");
```

### String Methods and Concatenation

> **Syntax & Example**: 
```js
const firstName = "Tahmid";
const lastName = "Sarker";

const fullName = firstName + lastName;
console.log(fullName);
console.log(typeof fullName);

// Concatenation
console.log(firstName + " " + lastName);

console.log("Hello " + firstName + " " + lastName + "Welcome to JavaScript!");

// Append
let name1 = "Tahmid ";
name1 += "Sarker";
console.log(name1);

// concat() method
console.log(firstName.concat(" ", lastName));

// Length
console.log(firstName.length);

// Change case
console.log(firstName.toLowerCase());
console.log(firstName.toUpperCase());

// Escaping
let statement1 = "wait I'm coming, that's good";
let statement2 = 'wait I\'m coming, that\'s good';

// String array - get specific character from string like an array
console.log(firstName[0]);

// indexOf
console.log(firstName.indexOf("i"));
console.log(firstName.lastIndexOf("a"));

// charAt()
console.log(firstName.charAt(2));

// Get last character from string
console.log(firstName.charAt(firstName.length - 1));

// replace();
let replaceString = firstName.replace("Tahmid", "DJ");
console.log("My name is:", replaceString);

// substring();
console.log(firstName.substring(0, 4));

// slice();
console.log(firstName.slice(0, 4));

// slice(); negative number starts from backside
console.log(firstName.slice(-2));

// includes();
let message2 = "Hello Tahmid, welcome to JavaScript";
console.log(message2.includes("Hello"));
console.log(message2.includes("Hi"));

// split()
let message3 = "Hello Tahmid, welcome, to JavaScript";
console.log(message3.split(","));
console.log(message3.split(" "));

let courses = "html5, css3, javascript, angular";
console.log(courses.split(","));
```

### Template String

- ES6 new feature `Strings Template` offers a convenient way to work with string concatenation/interpolation.
- Template literals provide an easy and clean way to create multi-line strings and perform string interpolation.
- Intuitive expression interpolation for single-line and multi-line strings.
- Use `back-tick (grave accent)` character and `{ var name in curly brace }`, no + plus sign required.
- The best part of Template Literals (Template Strings) is that we can use 'single' "double" quotes inside.

- It is part of ES6 but compatible with all modern browsers and their latest versions.

> **Syntax & Example**
```js
// Old plain JavaScript approach
let user = "Tahmid";
let greetMessage1 = "Welcome" + " " + user + " " + "to JavaScript.";

console.log(greetMessage1);

console.log("// ------------------------------");

const firstName = "Tahmid";
const lastName = "Sarker";
const course = "JavaScript";

const fullName = `Hey ${firstName} ${lastName} Welcome to ${course}.`;

console.log("// ------------------------------");

// ES6 Template Literals (Template Strings) approach
let greetMessage2 = `Hello ${firstName}, How are you?`;

console.log(greetMessage2);

console.log("// ------------------------------");
// ------------------------------

// ES6 multi-line string
let greetMessage3 = `ES6 Template Literals (Template Strings):
                    With Template Literals (Template Strings)
                    we can add multiple lines in string concatenation/interpolation`;

console.log(greetMessage3);

let greetMessage4 = `ES6 Template Literals (Template Strings):
                    With Template Literals (Template Strings)
                    we can add multiple lines in string concatenation/interpolation`;

console.log(greetMessage4);
```

## Loops

- Loops are used to execute the `same block of code again, with a different value, until a certain condition is met`.
- Loops can execute/repeat a block of code (an action) a number of/several times.
- The basic idea behind a loop is to `automate the repetitive tasks within a program to save time and effort`.
- It makes the `code compact`.
- It is mostly used in arrays or objects (to iterate through series).
- Loops/iterations are instructions that repeat until a specific condition is reached.

#### Different Types of Loops in JavaScript:

1. for loop
2. while loop
3. do...while loop
4. for...in loop
5. for...of loop (ES6)
6. for...each

### The for loop

- The `for` loop is used to run a piece of code a `set amount of times`.
- Loops through a block of code until the `counter reaches a specified number`.
- The for loop `repeats a block of code until a certain condition` is met.
- The for loop is the most simple/compact form of looping.
- For loop consists of 3 statements (). Mostly, `i = index` is used for loop initialization.

> **Syntax & Example**
```js
// for loop

/* 
for (statement 1; statement 2; statement 3) {
  // Code to be executed
} */

/* 
for (variable definition/index/initialization; condition checking; increment/decrement expression) {
  // Code to be executed
} */

for (let i = 1; i <= 5; i++) {
  alert("Hello, The current index/num is: " + i);
  document.write("<li>Hello, The current index/num is: " + i + "</li>");
  console.log("Hello, The current index/num is: " + i);
}
```

#### The for loop - Reverse order

> **Syntax & Example**
```js
// for loop - reverse order

for (let i = 5; i >= 1; i--) {
  alert("Hello, The current index/num is: " + i);
  document.write("<li>Hello, The current index/num is: " + i + "</li>");
  console.log("Hello, The current index/num is: " + i);
}
```

#### The for loop - Find Even or Odd number

> **Syntax & Example**
```js
// for loop - to find out odd even number

for (let i = 1; i <= 10; i++) {
  if (i % 2 === 0) {
    console.log("The current index/num is EVEN: " + i);
  } /* else {
    console.log('The current index/num is ODD : ' + i);
  } */
}
```

### The while loop

- Loops through a block of code until the specified condition evaluates to true.
- In the For loop, a variable is part of the loop, but in the While loop, we need to declare the variable externally.

> **Syntax & Example**
```js
// while loop

/* 
while (condition) {
  // Code to be executed
}
*/

let i = 1;

while (i <= 5) {
  alert("Hello, The current index/num is: " + i);
  document.write("<li>Hello, The current index/num is: " + i + "</li>");
  console.log("Hello, The current index/num is: " + i);
  i++;
}
```

### The do while loop

- The do...while loop is similar to the while loop except that the `condition check happens at the end of the loop`.
- The do...while loop will always be `executed at least once (before checking if the condition is true)`, even if the condition is false.

> **Syntax & Example**
```js
// do...while loop

/* 
do {
    // Code to be executed
}
while (condition);
*/

let i = 1;

do {
  alert("Hello, The current index/num is: " + i);
  document.write("<li>Hello, The current index/num is: " + i + "</li>");
  console.log("Hello, The current index/num is: " + i);
  i++;
}
while (i <= 5);
```

### The for in loop

- The for-in loop is a special type of loop that `iterates over the properties of an object or the elements of an array`.

#### The for...in Loop - array

> **Syntax & Example**
```js
// for...in loop

/* 
for (variable/key in array/object) {
    // Code to be executed
}
*/

// An array with some elements
let arrColors = ["Red", "Green", "Blue", "Cyan", "Magenta", "Yellow", "Black"];

// Loop through all the elements in the array 
for (let index in arrColors) {
  alert("Color is: " + arrColors[index]);
  document.write("<li>Color is: " + arrColors[index] + "</li>");
  console.log("Color is: " + arrColors[index]);
}
```

#### The for...in Loop - object

> **Syntax & Example**
```js
// for...in loop

/* 
for (variable/key in array/object) {
    // Code to be executed
}
*/

// An object with some properties 
let objEmployee = {"emp_name": "Tahmid", "emp_address": "Dhaka", "emp_id": "011", "emp_age": 25};

// Loop through all the properties in the object  
for (let emp in objEmployee) {
  alert("Employee " + emp + " is: " + objEmployee[emp]);
  document.write("<li>Employee " + emp + " is: " + objEmployee[emp] + "</li>");
  console.log("Employee " + emp + " is: " + objEmployee[emp]);
}
```

#### The for...in Loop - Inbuilt JavaScript objects

> **Syntax & Example**
```js
// for...in loop

/* 
for (variable/key in array/object) {
    // Code to be executed
}
*/

// Loop through all the properties in the built-in object - window, document, navigator
for (let props in window) {
  document.write("<li>document object properties " + props + "</li>");
  console.log("document object properties " + props);
}
```

### The for of loop

- Loops over iterable objects such as arrays and strings.
- ES6 introduces a new for-of loop, which allows us to iterate over arrays or strings very easily.
- The code inside the loop is executed for each element of the iterable object.

> **Syntax & Example**
```js
// for...of loop

/* 
for (element of array/string) {
  // Code to be executed
} 
*/

// Iterating over an array
let arrDays = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"];

for (let day of arrDays) {
  console.log(day);
  document.write("<li>" + day + "</li>");
}

// Iterating over a string
let name = "JavaScript";
for (let letter of name) {
  document.write(letter + ",");
  console.log(letter + ",");
}
```

### Break and Continue statement

- `break` and `continue` keywords/statements can change how the loop behaves.
- `break` and `continue` keywords can be used in all loops to stop or continue the loop.
- The `break` statement is used to exit a loop early, to "jump out" of a loop, and stops executing/running the loop.
- The `continue` statement tells the interpreter to immediately start the next iteration of the loop and skip the remaining code block.

> **Syntax & Example**
```js
// break continue statement

/* break */
let arrDays = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"];

// Using break with while loop
let i = 1;
while (i <= 10) {
  if (i == 5) {
    break;
  }
  console.log(i);
  i++;
}

console.log("// ------------------------------");

// Using break with for loop
for (let i = 0; i < arrDays.length; i++) {
  if (i == 3) {
    break;
  }
  console.log(arrDays[i]);
}

console.log("// ------------------------------");

/* continue */
// Using continue with while loop
i = 1;
while (i <= 20) {
  if (i % 2 == 0) {
    i++;
    continue; // Skip rest of the loop body for even numbers
  }
  console.log("Odd Number ", i);
  i++;
}

console.log("// ------------------------------");

// Using continue with for loop
for (i = 1; i <= 10; i++) {
  if (i === 5) {
    continue; // Skip rest of the loop body when i equals 5
  }
  console.log(i);
}

console.log("// ------------------------------");

// Using break and continue in a loop
for (let int = 0; int < 10; int++) {
  if (int === 2) {
    console.log("2 is favorite EVEN number");
    continue;
  }
  if (int === 5) {
    console.log("At 5, stop the loop");
    break;
  }
  console.log("Current Number is:", int);
}
```

### for each loop

> **Syntax & Example**
```javascript
let arrDays = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"];

arrDays.forEach(function(day) {
  console.log(day);
});
```

## Conditions

- Conditional statements are used to perform different actions based on different conditions.
- Conditional statements allow the developer to make correct decisions and perform the right actions as per the condition.
- It helps to perform different actions for different decisions.
- We can use conditional operators to check our conditions: >, <, >=, <=, ==, !=, ===.

#### We can use the following conditional statements in JavaScript to make decisions:

1. If Statement
2. If...else Statement
3. If...else if...else Statement
4. Switch...Case Statement

### The if statement

- If the conditional statement is the simplest and basic control statement to make decisions and execute statements conditionally.
- The if statement is used to execute a block of code `only if the specified condition evaluates to true`.
- It evaluates the content only `if an expression is true`.

If conditional statements are used to evaluate some kind of condition and do something or perform some actions based on the result.

> [!TIP]\
Use `if` to specify a block of code to be executed if a specified condition is true.

> **Syntax & Example**
```js
// if conditional statement

/* 
if (condition/expression) {
  // Code to be executed if condition/expression is true
}
*/

// Example 1: Greeting for authorized user
let user = "Tahmid";

if (user == "Tahmid") {
  console.log("Welcome Tahmid!");
  window.alert("Welcome Tahmid!");
}

// Example 2: Customized greeting for authorized user
if (user == "Tahmid") {
  console.log("Welcome Authorized User: " + user + "!");
  window.alert("Welcome Authorized User: " + user + "!");
}

// ------------------------------

// Example 3: Eligibility check for voting
let age = 20;

if (age >= 18) {
  console.log("MAJOR! Eligible for Voting");
  window.alert("MAJOR! Eligible for Voting");
}

// ------------------------------

// Example 4: Greeting based on time of day
let currentHours = 10;

if (currentHours < 12) {
  console.log("Good Morning!");
  window.alert("Good Morning!");
}

// Additional condition
if (currentHours >= 6 && currentHours < 12) {
  console.log("Good Morning!");
  window.alert("Good Morning!");
}
```

### The if else statement

- The JavaScript `if...else` statement is used to execute the code `weather condition is true or false`.
- The developer can enhance the decision-making capabilities by providing an alternative choice through adding an `else` statement to the `if` statement.
- The condition can be any expression that evaluates to true or false.
- If the condition evaluates to true, statements_1 are executed; otherwise, statements_2 are executed.

> [!TIP]\
Use `else` to specify a block of code to be executed if the same condition is false.

> **Syntax & Example**
```js
// if...else conditional statement

/* 
if (condition/expression) {  
    // Content to be executed if condition is true - statements_1  
}  
else {  
    // Content to be executed if condition is false - statements_2
}
*/

// Example 1: Welcome message based on user
let user = "Sarker";

if (user == "Tahmid") {
  console.log("Welcome Tahmid!");
  window.alert("Welcome Tahmid!");
} else {
  console.log("Welcome Guest!");
  window.alert("Welcome Guest!");
}

// ------------------------------

// Example 2: Determining eligibility for voting based on age
let age = 15;

if (age >= 18) {
  console.log("MAJOR! Eligible for Voting");
  window.alert("MAJOR! Eligible for Voting");
} else {
  console.log("MINOR! NOT Eligible for Voting");
  window.alert("MINOR! NOT Eligible for Voting");
}

// ------------------------------

// Example 3: Greeting message based on current time
let currentHours = 10;

if (currentHours < 12) {
  console.log("Good Morning!");
  window.alert("Good Morning!");
} else {
  console.log("Good Evening!");
  window.alert("Good Evening!");
}
```

### The if else if else statement

- The `if...else if...else` is a special statement that is used to `combine multiple if...else statements`.
- It is an advanced form of if...else that allows us to `make a correct decision out of several conditions`.

> [!TIP]\
Use `else if` to specify a new condition to test, `if the first condition is false`.

> **Syntax & Example**
```js
// If...else if...else conditional statement

/* 
if (condition/expression 1) {
    // Code to be executed if condition1 is true (statements_1)
} else if (condition/expression 2) {
    // Code to be executed if condition1 is false and condition2 is true (statements_2)
} else {
    // Code to be executed if both condition1 and condition2 are false (statements_3)
}
*/

// Example 1: Comparing two numbers
let num1 = 200;
let num2 = 100;

if (num1 == num2) {
  console.log("Both numbers are equal");
} else if (num1 < num2) {
  console.log("Number2 is greater!");
} else {
  console.log("Number1 is greater!");
}

// ------------------------------

// Example 2: Determining age category
let age = 15;

if (age >= 60) {
  console.log("SENIOR CITIZEN!");
} else if (age < 18) {
  console.log("MINOR!");
} else {
  console.log("MAJOR - Middle Age!");
}

// ------------------------------

// Example 3: Greeting message based on time of the day
let currentHours = 15;

if (currentHours >= 6 && currentHours < 12) {
  console.log("Good Morning!");
  window.alert("Good Morning!");
} else if (currentHours >= 12 && currentHours <= 18) {
  console.log("Good Afternoon!");
  window.alert("Good Afternoon!");
} else {
  console.log("Good Evening!");
  window.alert("Good Evening!");
}
```

### The switch case statement

- The switch...case statement is an alternative to an if...else if...else statement. Both do almost the same thing.
- This matches the `case` and the `value of the condition`, and if the case matches, the subsequent block is executed. If none of the cases match, the `default` block is executed.
- The JavaScript switch statement is used to execute one code from multiple blocks of expressions.

> [!TIP]\
Use `switch` to specify many `alternative blocks of code to be executed`.

> **Syntax & Example**
```js
// switch...case conditional statement

/* 
  switch(variable/expression){
    case value1:
      // Code to be executed if variable/expression === value1
      break;
    case value2:
      // Code to be executed if variable/expression === value2
      break;
    default:
      // Code to be executed if variable/expression is different from all values
  } 
*/

// Example 1: Grading system
let grade = "B";

switch (grade) {
  case "A":
    console.log("Great Job! - A Grade");
    break;
  case "B":
    console.log("Good! - B Grade");
    break;
  case "C":
    console.log("Congratulations! - Passed");
    break;
  default:
    console.log("Sorry! - Failed...Keep trying!");
    break;
}

// Example 2: Sweets preference
let sweets = "cake";

switch (sweets) {
  case "chocolates":
    console.log("Chubby Chocolates!");
    break;
  case "cake":
    console.log("Happy Eid Cake!");
    break;
  case "biscuits":
    console.log("Enjoy Biscuits!");
    break;
  default:
    console.log("No Sweets! Try some other sweets!");
    break;
}

// Example 3: Color selection
const color = "red";

switch(color) {
  case "red":
    console.log("The Dark RED");
    break;
  case "green":
    console.log("Go Green");
    break;
  case "blue":
    console.log("Boys are Blue");
    break;
  case "yellow":
    console.log("Golden Yellow");
    break;
  default:
    console.log("It's some other Color, Enter correct color");
    break;
}

// Example 4: Current day of the week
let currentDate = new Date();
let currentDay;

switch(currentDate.getDay()) {
  case 0:
    currentDay = "Sunday";
    break;
  case 1:
    currentDay = "Monday";
    break;
  case 2:
    currentDay = "Tuesday";
    break;
  case 3:
    currentDay = "Wednesday";
    break;
  case 4:
    currentDay = "Thursday";
    break;
  case 5:
    currentDay = "Friday";
    break;
  case 6:
    currentDay = "Saturday";
    break;
}

console.log("Today is " + currentDay + "!");
```

## Array

### What is an Array?

- An Array is a special type of variable/object which consists of / stores multiple values.
- Arrays are complex variables that allow us to store more than one value or a group of values under a single variable name.
- Arrays are defined with square brackets [ ] and with the new keyword.
- Array items are normally separated with commas.
- Arrays are zero-indexed, i.e. the first element of an array is at index/position 0.
- An array is an ordered collection, where we have a 0th, 1st, 2nd, and so on elements.
- Each value (an element) in an array has a numeric position, known as its index, starts from 0, so that the first array element position/index is arr[0], not arr[1].

#### Different ways to create/define an Array

There are 3 main ways to construct an array:
1. By array literal 
2. By creating an instance of Array directly (using the new keyword)
3. By using an Array constructor (using the new keyword)

### Create Array by array literal

- The simplest way to create an array in JavaScript is by enclosing a comma-separated list of values in square brackets [ ].

> **Syntax & Example**
```js
// Create array using array literal ([])
// var myArray = [element0, element1, ..., elementN];

// Example 1: Creating an array of colors
var arrColors = ["Red", "Green", "Blue", "Orange"];
console.log(arrColors); // Show all elements

// ------------------------------

// Example 2: Creating an array of cities
var arrCities = ["Dhaka", "Sunamganj", "Sylhet", "Makkah", "Madinah"];
console.log(arrCities[1]); // Show 1st index ie. 2nd positioned element

// ------------------------------

// Example 3: Creating an array of technologies
var arrTechnologies = [];
arrTechnologies[0] = "Java";
arrTechnologies[1] = "Python";
arrTechnologies[2] = "C";
console.log(arrTechnologies);
console.log("Total Elements: " + arrTechnologies.length);
```

### Create Array by creating an instance of array directly

- Array instance can be created using the `new` keyword `new Array()`

> **Syntax & Example**
```js
// Create array using the new Array constructor
// var myArray = new Array(); OR var myArray = Array();

// Example 1: Creating an array of colors
var arrColors = new Array();

arrColors[0] = "Red";
arrColors[1] = "Green";
arrColors[2] = "Blue";
arrColors[3] = "Orange";
console.log(arrColors); // Show all elements

// Read/get array items/elements
for (let i = 0; i < arrColors.length; i++) {
  alert(arrColors[i]);
}

// ------------------------------

// Example 2: Creating an array of cities
var arrCities = Array(); 
arrCities[0] = "Dhaka";
arrCities[1] = "Sunamganj";
arrCities[2] = "Sylhet";
arrCities[3] = "Makkah";
arrCities[4] = "Madinah";
console.log(arrCities); // Show all elements

// ------------------------------

// Example 3: Creating an array of technologies
var arrTechnologies = new Array();

// Add new array items/elements
for (let i = 0; i <= 5; i++) {
  arrTechnologies[i] = "JavaScript";
}

console.log(arrTechnologies); // Show all elements
```

### Create Array by using an array constructor

- Array instances can be created using the `new` keyword and passing arguments in the constructor, so we don't have to provide values explicitly.

> **Syntax & Example**
```js
// Create array using the new Array constructor with parameters
// var myArray = new Array(element0, element1, ..., elementN);

// Example 1: Creating an array of colors
var arrColors = new Array("Red", "Green", "Blue", "Orange");
console.log(arrColors); // Show all elements

// ------------------------------

// Example 2: Creating an array of cities
var arrCities = new Array("Dhaka", "Sunamganj", "Sylhet", "Makkah", "Madinah");
console.log(arrCities); // Show all elements

// ------------------------------

// Example 3: Creating an array of JavaScript frameworks
var arrJsFrameworks = new Array("jQuery", "Angular", "React", "Node", "Vue", "Express", "D3");
console.log(arrJsFrameworks); // Show all elements
```

### Getting the Length of an Array

- The `length` property returns the `length of an array`, which is the `total number of elements` in the array.
- The `length` property represents the fixed amount of items stored in the array.
- The array length is always greater than the index of any of its elements. (Array length = last array index + 1)
- The maximum length allowed for an array is `4,294,967,295`.

> **Syntax & Example**
```js
// Get/retrieve/find array length
// myArray.length

// Example 1: Finding the length of an array
var arrColors = new Array("Red", "Green", "Blue", "Orange");
console.log(arrColors.length);

// ------------------------------

// Example 2: Finding the length of an array
var arrCities = new Array("Dhaka", "Sunamganj", "Sylhet", "Makkah", "Madinah");
console.log(arrCities.length);

// ------------------------------

// Example 3: Finding the length of an array
var arrJsFrameworks = new Array("jQuery", "Angular", "React", "Node", "Vue", "Express", "D3");
console.log(arrJsFrameworks.length);
```

### Accessing Looping through an Array Elements

- Array elements can be accessed by their `index` using the square bracket notation, i.e., `[index]`.
- Arrays are `zero-indexed`, i.e., the first element of an array is at index/position 0.
- An array is an `ordered collection`, where we have a 0th, 1st, 2nd, and so on elements.
- Each value (an `element`) in an array has a `numeric position`, known as its `index`, starting from 0, so that the first array element is `arr[0]`, not `arr[1]`.
- One can use a `for loop` in coordination with the array `length` property to access each element of an array in sequential order.

> **Syntax & Example**
```js
// Access/loop through array elements
// myArray[index]

// Example 1: Accessing elements by index
var arrColors = new Array("Red", "Green", "Blue", "Orange");

console.log(arrColors[0]); // Red
console.log(arrColors[2]); // Blue

// ------------------------------

// Example 2: Accessing elements by index
var arrCities = new Array("Dhaka", "Sunamganj", "Sylhet", "Makkah", "Madinah");
console.log(arrCities[1]); // Sunamganj"
console.log(arrCities[4]); // Madinah

// ------------------------------

// Example 3: Accessing elements by index
var arrJsFrameworks = new Array("jQuery", "Angular", "React", "Node", "Vue", "Express", "D3");
console.log(arrJsFrameworks[3]); // Node
console.log(arrJsFrameworks[5]); // Express

// Loop through an array's elements
for (let i = 0; i < arrJsFrameworks.length; i++) {
  document.write("<li>" + arrJsFrameworks[i] + "</li>");
}
```

### Adding Editing an Array Elements

- One can add/edit an array element by simply specifying `array[index]` and `value`, i.e., `myarray[5]='value'`.
- If the array `index exists`, it will simply edit the old value and update the array; otherwise, it will add an element to the array.
- The `push()` method adds a new element at the end of an array.
- The `unshift()` method adds a new element at the beginning of an array.

> **Syntax & Example**
```js
// Add/edit array element
// myarray[indexNumber]="value", myarray[2]="value", myarray.push("value"), myarray.unshift("value")

// Methods to add/edit array elements:
// myarray[indexNumber] = "value", myarray.push("value"), myarray.unshift("value")

// Array of colors
var arrColors = new Array("Red", "Green", "Blue", "Orange");
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// Adding an element at the end of the array
arrColors.push("Cyan");
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// Adding multiple elements at the end of the array
arrColors.push("Magenta", "Yellow");
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// ------------------------------

// Adding multiple elements at the start of the array
arrColors.unshift("Black", "White");
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// ------------------------------

// Editing the element at index 1 from "White" to "Pink"
arrColors[1] = "Pink";
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);
```

### Removing Deleting an Array Elements

- The `pop()` method removes the last element from an array.
- The `shift()` method removes the first element from an array.

> [!TIP]\
The `push() and pop() methods run faster` than `unshift()` and `shift()`. Because the `push()` and `pop()` methods add and remove elements at the end of an array, therefore, the elements do not move, while `unshift()` and `shift()` add and remove elements at the beginning of the array, which requires re-indexing/re-structuring of the whole array.

> **Syntax & Example**
```js
// remove array element from start and end
// myarray.pop(), myarray.shift()

var arrColors = new Array("Red", "Green", "Blue", "Orange");
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// remove an element from the end of the array
arrColors.pop();
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);

// ------------------------------

// remove an element from the start of the array
let startElement = arrColors.shift();
console.log(startElement);
console.log(arrColors);
console.log("arrColors.length: " + arrColors.length);
```

### Array properties and methods

> **Syntax & Example**
```js
// length
var arrColors = new Array("Red", "Green", "Blue", "Orange");
console.log(arrColors.length);

// isArray() - check if array (check the type of variable is array)
var arrCities = new Array("Dhaka", "Sunamganj", "Sylhet", "Makkah", "Madinah");
console.log(Array.isArray(arrCities));
console.log(Array.isArray("I am Tahmid"));

// indexOf() - get index/location of provided value
var arrJsFrameworks = new Array("jQuery", "Angular", "React", "Node", "Vue", "Express", "D3");
console.log(arrJsFrameworks.indexOf("React"));

// Splice values
console.log(arrJsFrameworks.splice(1, 3));

// Reverse array
console.log(arrJsFrameworks.reverse());

// Concatenate array
let newArray = arrColors.concat(arrCities);

// sort
let newSortedColorsArray = arrColors.sort();
console.log(newSortedColorsArray);
console.log(numberArray.sort());

/* exact ascending sort
let sortedValues = numberArray.sort(function(num1,num2){
  return num1 - num2;
})
*/

/* exact descending sort
let sortedValues = numberArray.sort(function(num1,num2){
  return num2 - num1;
})
*/

// find
console.log(numberArray.find(40));
```

## Objects

### Real Life Objects

- In real life, almost `everything is an object`. 
  - For example: Human, Car, Building, Bike, Pen, Chair, Monitor, Keyboard, Vehicle, Mobile, Computer, etc.
- Let's have a look on some Objects with Properties and Methods:

| Object  | Properties                                                  | Methods                          |
|---------|-------------------------------------------------------------|----------------------------------|
| Person  | Person.name = "Tahmid"; <br/> Person.weight = 65; <br/> Person.color = "fair" | Person.walk(); <br/> Person.talk(); <br/> Person.eat(); |
| Bike    | Bike.brand = "Bajaj"; <br/> Bike.model = "discover"; <br/> Bike.color = "blue"; <br/> Bike.length = 60; <br/> Bike.height = 30; | Bike.start(); <br/> Bike.break(); <br/> Bike.stop(); |
| Watch   | Watch.type = "analog"; <br/> Watch.price = 1000;              | Watch.showTime(); <br/> Watch.setAlarm(); |

> [!TIP]\
As a practice, think of any other object in your surrounding and list its Properties and Methods.

### What is an Object?

- JavaScript is an `object-based language`, and in JavaScript, almost everything is an object or acts like an object.
- An object is a `special/complex` data type that allows you to `store collections of data`.
- An object is a kind of container/declaration where we can group various `data, properties, and behaviors` under one roof (group related variables).
- A JavaScript object is just a collection of `named values referred to as properties` of the object.
- Objects are defined with `curly braces { }`. The properties of an object are written in pairs (`propertyName: value`).
- An object contains properties, defined as a `key-value pair`. Objects are a collection of `key-value pairs`.
- A property `key (name) is always a string`, but the value which it stores can be any data type, like strings, numbers, booleans, or complex data types like arrays, functions, and other objects.
- JavaScript object properties can be accessed through two methods:
  1. .DOT notation: `object.firstName`
  2. []Bracket notation: `object['firstName']`

### Different ways to create/define an Object

There are 3 main ways to construct an object:
1. By object literal 
2. By creating an `instance` of Object directly (using `new` keyword)
3. By using an `Object constructor` (using `new` keyword)

### Object literal

- The simplest way to create an object in JavaScript is by enclosing a `comma-separated list of properties:values and methods in curly braces { }`.

> **Syntax & Example**
```js
// Create object with object literal
// var MyObject = { property1: value1, property2: value2.....propertyN: valueN }  

// Empty object
var HumanObj = {};

console.log(HumanObj);

console.log("// ------------------------------");

// Object with properties
var TechnologyObj = { "name": "JavaScript", "version": 6, "type": "script", "isStable": true };

console.log(TechnologyObj.name);
console.log(TechnologyObj["isStable"]);

console.log("// ------------------------------");

// Object properly aligned for readability with quotes
var VehicleObj1 = {
  "type": "LWM",
  "brand": "Maruti",
  "model": "Alto-100",
  "color": "White",
  "isHighEndModel": true,
  "price": 400000,
  keyStart: function () {
    console.log(this.model + " started!");
  }
};

console.log(VehicleObj1.brand);
console.log(VehicleObj1["color"]);
VehicleObj1.keyStart();

console.log("// ------------------------------");

// Object properly aligned for readability without quotes
var VehicleObj2 = {
  type: "LWM",
  brand: "Maruti",
  model: "Alto-100",
  color: "White",
  isHighEndModel: true,
  price: 400000,
  keyStart: function () {
    alert(this.model + " started!");
  }
};

console.log(VehicleObj2.brand);
console.log(VehicleObj2["color"]);
VehicleObj2.keyStart();

console.log("// ------------------------------");
```

### Creating an instance of Object directly

- An array instance can be created using the `new` keyword `new Array()` with or without passing arguments/properties-methods in the constructor.

> **Syntax & Example**
```js
//var MyObject = new Object(); OR var MyObject = Object();

// Create object with new keyword
var TechnologyObj = new Object();

// Define object properties
TechnologyObj.name = "JavaScript";
TechnologyObj.version = 6;
TechnologyObj.type = "script";
TechnologyObj.isStable = true;

console.log(TechnologyObj.name);
console.log(TechnologyObj["type"]);

console.log("// ------------------------------");

// Object properly aligned with quotes for readability
var VehicleObj1 = {
  "type": "LWM",
  "brand": "Maruti",
  "model": "Alto-100",
  "color": "red",
  "isHighEndModel": true,
  "price": 400000,
  keyStart: function () {
    console.log(this.model + " started!");
  }
};

// Access property with DOT notation
console.log(VehicleObj1.brand);

// Access property with Bracket notation
console.log(VehicleObj1["color"]);
VehicleObj1.keyStart();

console.log("// ------------------------------");

// Object properly aligned without quotes
var VehicleObj2 = {
  type: "LWM",
  brand: "Tata",
  model: "Safari",
  color: "White",
  isHighEndModel: false,
  price: 1400000,
  keyStart: function () {
    alert(this.model + " started!");
  }
};

// Access property with DOT notation
console.log(VehicleObj2.brand);

// Access property with Bracket notation
console.log(VehicleObj2["color"]);
VehicleObj1.keyStart();

console.log("// ------------------------------");
```

### Object constructor

- In this method, create a function with arguments.
- Each argument value can be assigned to the current object by using the `this` keyword. The `this` keyword refers to the current object.

> **Syntax & Example**
```js
// Creating an object using the new keyword with the Object constructor function

// Define a constructor function for Technology
function Technology(name, version, type) {
  this.name = name;
  this.version = version;
  this.type = type;
  console.log(this.name);
  console.log(this.type);
}

// Creating an instance of Technology
let JavaScript = new Technology("JavaScript", 6, "Script Language");
console.log(JavaScript.version);

console.log("// ------------------------------");

// Define a constructor function for Vehicle
function Vehicle(brand, model, color, price) {
  this.brand = brand;
  this.model = model;
  this.color = color;
  this.price = price;
  this.keyStart = function() {
    console.log(this.model + " started!");
  };
}

// Creating an instance of Vehicle
var Maruti = new Vehicle("Maruti", "Alto-100", "White", 400000);
Maruti.keyStart();

console.log("// ------------------------------");
```

### Accessing objects properties

- To access or get the value of a property, you can use the `dot .`, or `square bracket []` notation.
- We can iterate through the `key-value` pairs of an object using the `for...in` loop.

> **Syntax & Example**
```js
//MyObject.propertyName; OR MyObject[propertyName]; OR MyObject['propertyName']

// Accessing object properties
var Person = {
  name: "Tahmid",
  domain: "IT/Software",
  gender: "Male",
  city: "Dhaka",
  country: "Bangladesh"
};

console.log(Person.name); // Accessing property using dot notation
console.log(Person['domain']); // Accessing property using bracket notation

console.log("// ------------------------------");

// Looping through object properties
for (var prop in Person) {
  console.log(Person[prop]);
}

console.log("// ------------------------------");
```

### Removing Deleting objects properties

- The `delete` operator can be used to completely remove properties from an object.

> [!TIP]\
The `delete` operator only removes an `object property or array element`. It does not work/does not affect variables or declared functions.

> **Syntax & Example**
```js
// Removing/deleting object properties
// delete MyObject.propertyName;

var Person = {
  name: "Tahmid",
  domain: "IT/Software",
  gender: "Male",
  city: "Dhaka",
  country: "Bangladesh"
};

delete Person.name; // Removing the 'name' property
console.log(Person); // Outputting the modified object
console.log(Person.name); // Outputting undefined as the 'name' property no longer exists
console.log(Person["domain"]); // Accessing the 'domain' property using bracket notation
```

### Manipulating by Value Vs Reference

In JavaScript we have two categories of types:
1. Value Types (Primitives = Basic type) - Primitives are copied by their value
2. Reference Types (Objects = Complex type) - Objects are copied by their Reference/Location in memory

#### 1. Value Types (Primitives)

  1. Number
  2. String
  3. Boolean
  4. Undefined
  5. Null
  6. Symbol (ES6)

#### 2. Reference Types (Objects)

  1. Object
  2. Function 
  3. Array

> **Syntax & Example**
```js
// Value Types (Primitives) - copied by their value
// Example 1: Value Types (Primitives) - copied by their value
let x = 10;
let y = x;

x = 20;
console.log(x); // 20
console.log(y); // 10

console.log("// ------------------------------");

// Reference Types (Objects) - copied by their Reference/Location in memory
// Example 2: Reference Types (Objects) - copied by their Reference/Location in memory
let a = { value: 10 };
let b = a;

a.value = 20;
console.log(a.value); // 20
console.log(b.value); // 20

console.log("// ------------------------------");
```

### The Window object 

- The Window Object is the global variable/global object `available in the browser environment` that represents the browser window in which the script is running.
- Simply put, the window object represents a window in a browser.
- The Window interface represents a window containing a DOM (Document Object Model).
- Window is the object of the browser (`The Browser Object Model (BOM)`); it is not the object of JavaScript.
- The Browser Object Model (BOM) allows JavaScript to "communicate/talk to" the browser.
- In the browser's "Inspect Element" -> "Console Panel" -> Type `Window`, you can check the different properties and methods available.

> **Syntax & Example**
```js
// Methods

// Logging a message to the console
window.console.log("Console! Hello, Welcome to JavaScript");

// Displaying an alert dialog box
window.alert("Alert! Hello, Welcome to JavaScript");

// Prompting the user to enter their name and displaying it in an alert dialog
const namePrompt = window.prompt("Enter Your Name");
window.alert(namePrompt);

// Asking the user to confirm an action
if (window.confirm("Are you sure?")) {
  window.console.log("YES - selected");
} else {
  window.console.log("NO - clicked");
}

// Properties

// Full browser window height and width
let outerHeight = window.outerHeight;
let outerWidth = window.outerWidth;

console.log("outerHeight -", outerHeight, "::", "outerWidth -", outerWidth);

// Document/page height and width
let innerHeight = window.innerHeight;
let innerWidth = window.innerWidth;

console.log("innerHeight -", innerHeight, "::", "innerWidth -", innerWidth);

// Scroll position
console.log("scrollY", window.scrollY);
console.log("scrollX", window.scrollX);

// Location

// Current window location/URL
console.log("current window location/url", window.location);
console.log("current window location/url", window.location.href);

// Location redirect
window.location.href = "https://www.google.com";

// Window location/visited history
window.history.go(-1);

let totalPagesVisitedHistory = window.history.length;

// Current browser details - navigator
let curBrowser = window.navigator.appName;
// window.navigator.userAgent;
window.navigator.platform;
window.navigator.vendor;
```

### The Math Object

- The Math object allows to perform mathematical tasks.
- The Math object provides several constants and methods to perform mathematical operations (such as `min`, `max`, `sqrt`, `pi`, `round`, `random`, etc).

> **Syntax & Example**
```js
let pieValue = Math.PI;

console.log(Math.E); // Euler's number
console.log(Math.round(2.6)); // Rounds to the nearest integer

console.log(Math.ceil(2.6)); // Rounds up to the nearest integer
console.log(Math.floor(2.6)); // Rounds down to the nearest integer

console.log(Math.sqrt(64)); // Square root of a number
console.log(Math.abs(-10)); // Absolute value (returns positive number)

console.log(Math.pow(8, 2)); // Exponential (8 raised to the power of 2 is 64)
console.log(Math.pow(10, 3)); // Exponential (10 raised to the power of 3 is 1000)

console.log(Math.min(20, 5, 9, 15, 2)); // Minimum value among the arguments
console.log(Math.max(20, 5, 9, 15, 2)); // Maximum value among the arguments

console.log(Math.random()); // Random number between 0 and 1
console.log(Math.random() * 20 + 1); // Random number between 1 and 20
console.log(Math.floor(Math.random() * 20 + 1)); // Random integer between 1 and 20 (inclusive)
```

### Date and Time

- The Date object is used to deal with dates and times.
- Simply put, the JavaScript Date object can be used to get the date, day, month, and year.
- Date objects are created with `new Date()`. The Date constructor can be used to create a date object. It provides methods to get and set the day, month, year, hour, minute, and second.

> **Syntax & Example**
```js
const today = new Date();
console.log("Today is:", today);

const date1 = new Date("March 29, 1980");
const date2 = new Date("09-10-1980");

let currentDate = new Date();

const currentDateToday = currentDate.getDate();
const currentDayToday = currentDate.getDay();
const currentMonth = currentDate.getMonth();
const currentYear = currentDate.getFullYear();
const currentHours = currentDate.getHours();
const currentMinutes = currentDate.getMinutes();

// Setting a new birth month (note: this modifies the current date object)
const newBirthDate = currentDate.setMonth(5);
console.log(newBirthDate);
```

## Events

### Understanding Events and Event Handlers

- Events are happening/triggering all over, Event lets the developer know `something has occurred/happened`
- Events occur when the page loads (Onload), when the user interacts with the web page (clicked a link or button/hover) (onlick), pressed key, moved the mouse pointer, mouse-clicked/hover (onmouseover), entered text into an input box or textarea (onchange, onblur, onfocus), submits a form (submit), page unloads (unload)
- When an event occurs, use a JavaScript `event handler (or an event listener) to detect` them and perform a specific task - Event handlers name always begin with the word `"on"`, like onclick, onload, onblur, and so on
- To react to an event you `listen` for it and supply a `callback function or event handler` which will be called by the browser when the event occurs

### Different Event category

In general, the events can be categorized into four main groups:
1. Mouse events
2. Keyboard events
3. Form events
4. Document/Window events

#### Mouse events

A mouse event is triggered when the user clicks on an element, moves the mouse pointer over an element, etc. Find here some of the important mouse events and their event handlers:

- **click** (`onclick` event handler)
  - Occurs when the mouse clicks on an element, such as links, buttons, etc., on a web page.
- **contextmenu** (`oncontextmenu` event handler)
  - Occurs when a user clicks the right mouse button on an element to open a context menu.
- **mouseover / mouseout** (`onmouseover` & `onmouseout` event handlers)
  - Occurs when the mouse pointer/cursor comes over/leaves (goes outside of) an element.
- **mousedown / mouseup** (`onclick/onmousedown` & `onmouseup`)
  - Occurs when the mouse button is pressed/released over an element.
- **mousemove** (`onmousemove` event handler)
  - Occurs when the mouse pointer/cursor is moved.

> **Syntax & Example**
```html
<ol class="normalList">
  <li>
    <strong>click</strong> (onclick event handler) <br/>
    <span onclick="alert('You have clicked an element!')" style="color: blue; cursor: pointer;">Occurs When the mouse clicks on an element, links, buttons etc. on a web page</span>
  </li>
  <li>
    <strong>contextmenu</strong> (oncontextmenu event handler) <br/>
    <span oncontextmenu="alert('You have Right clicked on Me!')" style="color: blue; cursor: pointer;">Occurs when a user clicks the right mouse button on an element to open a context menu</span>
  </li>
  <li>
    <strong>mouseover / mouseout</strong> (onmouseover & onmouseout event handler) <br/>
    <span onmouseover="console.log('You have Mouse Over Me!')" onmouseout="console.log('You have Mouse Out Me!')" style="color: blue; cursor: pointer;">Occurs when the mouse pointer/cursor comes over / leaves (goes outside of) an element</span>
  </li>
  <li>
    <strong>mousedown / mouseup</strong> (onclick/onmousedown & onmouseup) <br/>
    <span onmousedown="console.log('You have clicked on Me!')" onmouseup="console.log('You have released click on Me!')" style="color: blue; cursor: pointer;">Occurs when the mouse button is pressed / released over an element</span>
  </li>
  <li>
    <strong>mousemove</strong> (onmousemove event handler) <br/>
    <span onmousemove="console.log('You Moved mouse over Me!')" style="color: blue; cursor: pointer;">Occurs when the mouse pointer/cursor is moved</span>
  </li>
</ol>
```
<!--Change background color on mouse movement-->
```js
// Selecting the button element with class 'some-button'
const button = document.querySelector(".some-button");

// Selecting the heading element <h1>
const headingText = document.querySelector("h1");

// Adding an event listener to the button for mousemove event
button.addEventListener("mousemove", someFunction);

// Function to handle the mousemove event
function someFunction(event) {
  // Logging event details
  console.log("Event Details:", event);

  // Changing the text content of the heading element
  headingText.innerText = "Changed after click!";

  // Changing the background color of the document body based on mouse coordinates
  document.body.style.backgroundColor = `rgb(${event.offsetX},${event.offsetY},40)`;
}
```

#### Keyboard events 

A keyboard event is fired up when the user presses or releases a key on the keyboard. Here are some of the important keyboard events and their event handlers:

- **keydown / keyup** (`onkeydown` & `onkeyup` event handler)
  - Occurs when the user presses down a key and then releases the button/a key on the keyboard

> **Syntax & Example**
```html
<h1 id="headingText">This is heading</h1>
<label>Enter Name:</label>

<input
  type="text"
  placeholder="Enter Name"
  onkeydown="console.log('onkeydown pressed a key inside input text!')"
  onkeyup="console.log('onkeyup released a key inside input text!')"
/>
```

```js
const nameText = document.querySelector("input[type='text']");
const headingText = document.querySelector("#headingText");

// Change heading text on keydown event
nameText.addEventListener("keydown", nameData);
function nameData(event) {
  console.log("nameData function called");
  headingText.innerText = event.target.value;
}

// Change heading text on keyup event
nameText.addEventListener("keyup", function(event) {
  console.log("nameData function called");
  headingText.innerText = event.target.value;
});
```

#### Form events

A form event is triggered when a form control/form fields (text fields/radio buttons/checkbox) receives or loses focus or when the user modifies a form control value by typing text in a text input, select an option in a dropdown/select box, etc. Let us look into some of the most important form events and their event handler:

- **focus** (`onfocus` event handler)
  - Occurs when the user focuses on an element on a web page, e.g. on an `input` text field
- **blur** (`onblur` event handler)
  - Occurs when the user takes the focus away from a form element or a window
- **change** (`onchange` event handler)
  - Occurs when the user changes the value of a form element/fields
- **submit** (`onsubmit` event handler)
  - Occurs only when the user submits a form on a web page

> **Syntax & Example**
```html
<form action="" method="post" onsubmit="alert('Form data submitted to the server!');">

  <label>First Name:</label>
  <input type="text" name="first-name" onfocus="showHighlight(this)" onblur="resetHighlight(this)" required> <br/> <br/>

  <select onchange="console.log('You have selected something!');">
      <option>Select</option>
      <option>Male</option>
      <option>Female</option>
  </select> <br/> <br/>

  <input type="submit" value="Submit">
  
</form>
```

```js
// Function to highlight text field on focus
function showHighlight(curTxtField) {
  curTxtField.style.background = "pink";
}

// Function to reset text field highlight on blur
function resetHighlight(curTxtField) {
  curTxtField.style.background = "white";
}
```

```js
const personalDataForm = document.querySelector("form");

// Adding event listener for form submission
personalDataForm.addEventListener("submit", submitData);

// Function to handle form submission
function submitData(event) {
  console.log("submitData function called");
  // Preventing the default behavior of the form submission
  event.preventDefault();
}
```

#### Document/Window events

Events are happening and triggering all over. Events do trigger even when the page has loaded/unloaded or when the user resizes the browser window. Here are some of the most important document/window events and their event handlers:

- **DOMContentLoaded** (`DOMContentLoaded` event handler)
  - Occurs when the HTML is loaded and processed, and the DOM is fully built
- **load** (`onload` event handler)
  - Occurs when the web page has finished loading in the web browser
- **unload** (`onunload` event handler)
  - Occurs when a user leaves the current web page
- **resize** (`onresize` event handler)
  - Occurs when a user resizes the browser window, even when the browser window is minimized or maximized

> [!TIP]\
The unload event is not supported properly in most of the browsers.

> **Syntax & Example**
```html
<body onload="window.alert('Page loaded successfully!');" onunload="window.alert('Are you sure you want to leave this page?');">
```
```js
  // Resize window event handler
  window.onresize = resizeWindowSize;

  function resizeWindowSize() {
    console.log("window.outerWidth: " + window.outerWidth);
    console.log("window.outerHeight: " + window.outerHeight);
  }
```

### Different ways to write the event handler

1. HTML Attribute
2. DOM element properties (anonymous function)
3. Registering event listeners (Professional Method (add and remove listeners))

#### HTML attribute

> **Syntax & Example**
```html
<h2 onclick="window.alert('HTML attribute onclick used here!')" style="color:#0000ff; cursor:pointer">HTML attribute | Click Me!</h2>

<button onclick="alert('Hello world! Welcome to JavaScript Events!!')">Click here...</button>

<button onclick="fnShowMessage()">Invoke Function</button>
```
```js
// Event handler function
function fnShowMessage() {
  console.log("Welcome to fnShowMessage event handler!");
  alert("Welcome to fnShowMessage event handler!");
}
```

> [!TIP]\
This way should be avoided as it makes markup less readable and making it harder to find if there is any bug.

#### DOM element properties

> **Syntax & Example**
```html
<button id="messageButton1">Click here...</button>
<button id="messageButton2">Click here...</button>
```
```js
// DOM element properties

// Method 1: Using onclick property directly on the element
messageButton1.onclick = function() {
  console.log("Welcome to event handler!");
  alert("Welcome to event handler!");
};

// Method 2: Using getElementById and a named function
document.getElementById("messageButton2").onclick = fnShowMessage;

function fnShowMessage() {
  alert("Hello World! Welcome to JavaScript events");
}
```

#### Registering event listeners

> **Syntax & Example**
```js
// myButton.addEventListener('click', someFunc, false);

// Adding an event listener to the button with class 'clear-button'
document.querySelector(".clear-button").addEventListener("click", function() {
  console.log("clear-button clicked");
});
```

> [!TIP]\
This method is preferred in modern web pages. IE 6-8 do not support this method, there is an alternate for the `addEventListener` is `attachEvent` (myButton.attachEvent (‘onclick', someFunc);)

> **Syntax & Example**
```js
// Adding an event listener to the button with class 'clear-button'
document.querySelector(".clear-button").attachEvent("onclick", function() {
  console.log("clear-button clicked");
});
```

#### Event Bubbling Delegation

- Event Bubbling: bubbling up the event from bottom to top, i.e., from child to parent element.
- Event Delegation: Event Delegation is exactly the opposite of Event Bubbling. It simply means the event is passed from top to bottom, i.e., from parent to child element.

> **Syntax & Example**
```html
<ul id="list">
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
  <li>fourth item</li>
  <li>fifth item</li>
</ul>
```

```js
// Event Bubbling
document.getElementById("list").addEventListener("click", function(event) {
  console.log("Event Bubbling: " + event.target.innerText);
});

// Event Delegation
document.getElementById("list").addEventListener("click", function(event) {
  console.log("Event Delegation: " + event.target.innerText);
});
```

## DOM (Document Object Model)

### What is DOM?

- DOM represents the whole HTML document. DOM is a structure of an HTML web page where all tags are defined in a structured/structural way.
- The Document Object Model (DOM) is the model that describes how all elements in an HTML page (like input fields, images, paragraphs, headings, etc.) are related to the topmost structure: the document itself.
- DOM defines the logical structure of the documents and how they can be accessed and manipulated.
- DOM is a W3C (World Wide Web Consortium) standard that defines a standard for accessing documents. Programmers can build documents, navigate their structure, and add, modify, or delete elements and content.
- In the DOM world, always think in terms of `Nodes` (elements, attributes, text, etc.).

* Structural representation of an HTML document (Tree of nodes/elements/tags)

### Node

As we learned above, in the DOM, all parts of the document (like elements, their attributes, text, etc.) are organized in a hierarchical tree-like structure, similar to a real-life family tree that consists of parents and children. In DOM terminology, these individual parts of the document are known as `nodes`.

There are different types of nodes like: `Elements, Attribute & Text Node`.

> **Syntax & Example**
```html
<ul id="list"> <!-- Element & Attribute NODE -->
  <li>first item </li> <!-- text NODE -->
</ul>
<!-- Elements NODES do not contain text -->
```

> **Syntax & Example**
`In the Browser Window -> Inspect Element (Developer Tools) -> Console: type the following and check the output thoroughly`

- `document` - outputs the entire document/current page

- `document.all` - shows HTMLAllCollection(1532) [html, head, meta (html tags)]

- `document.url` - displays the current URL/path

### JavaScript DOM Selectors

JavaScript is commonly used to find or select, to get or modify the content/value of the HTML elements on the page, and as well as to apply some effects (like show, hide, add events, animate, etc.)

DOM selectors are nothing but methods that help to pull, traverse, and navigate elements and nodes from the document and perform operations on them.

Let's learn some of the common ways of selecting the elements on a page and do something using JavaScript.

#### Selecting Elements by ID (`getElementById()`)

- One can select an element based on its `unique ID` with the `getElementById()` method.
- `getElementById()` is the easiest and most common way to find/access an HTML element in the DOM tree.
- The `getElementById()` method returns the element with the given id value.

> **Syntax & Example**
```js
// Selecting the element with the ID 'mainHeadingText'
let mainHeadingElement = document.getElementById("mainHeadingText");

// Getting the HTML content of the selected element
let mainHeadingHtml = mainHeadingElement.innerHTML;

// Getting the text content of the selected element
let mainHeadingText = mainHeadingElement.innerText;
alert("mainHeadingHtml: " + mainHeadingHtml); // Text with complete HTML tags
alert("mainHeadingText: " + mainHeadingText); // Only text

// Setting the text of the selected element
mainHeadingElement.innerHTML = "This text changed with DOM method...";

// Selecting another element by ID
let subHeadingElement = document.getElementById("subHeadingText");

// Setting the text of the subheading element to match the main heading
subHeadingElement.innerHTML = mainHeadingElement.innerHTML;

// Setting CSS style for the main heading element
mainHeadingElement.style.backgroundColor = "pink";
```

#### Selecting Elements by Class Name (`getElementsByClassName()`)

- `getElementsByClassName()` method is used to select all the `elements having specific class names`
- The `getElementsByClassName()` method `returns an array of all elements` with the given class names

> **Syntax & Example**
```js
// Selecting elements with the class "list-item"
let listItems = document.getElementsByClassName("list-item");
console.log(listItems);

// Getting the text of the first (<0th>) element
let firstListItemText = listItems[0].innerHTML;
console.log("firstListItemText: " + firstListItemText);

// Setting the color of the last element to blue
let lastListItemIndex = listItems.length - 1;
listItems[lastListItemIndex].style.color = "blue";

// Highlighting all list items through a loop
for (let i = 0; i < listItems.length; i++) {
  listItems[i].style.marginBottom = "10px";
  listItems[i].style.background = "#bbbbbb";
}
```

#### Selecting Elements by Tag Name (`getElementsByTagName()`)

- Developers can also select HTML elements by tag name using the `getElementsByTagName()` method
- `getElementsByTagName()` method returns an array of all elements with the given tag name

> **Syntax & Example** 
```js
// Selecting all <li> elements by tag name
let liElements = document.getElementsByTagName("li");
console.log(liElements);

// Getting the total number of <li> elements in the page
let totalLiElements = liElements.length;
console.log(totalLiElements);

// Getting the text of the first (<0th>) <li> element
let firstLiText = liElements[0].innerHTML;
console.log("firstLiText: " + firstLiText);

// Setting the color of the last <li> element to blue
let lastLiIndex = liElements.length - 1;
liElements[lastLiIndex].style.color = "blue";

// Highlighting all <li> elements through a loop
for (let i = 0; i < liElements.length; i++) {
  liElements[i].style.marginBottom = "10px";
  liElements[i].style.background = "#bbbbbb";
}
```

#### Selecting Elements with CSS Selectors (`querySelectorAll()`)

- The `querySelectorAll()` method finds `all HTML elements that match a specified CSS selector` (id, class names, types, attributes, values of attributes, etc).
- CSS selectors provide a very `powerful and efficient way` of selecting HTML elements in a document.
- The `querySelectorAll()` method `returns an array` or list of all the elements that match the specified selectors.

> **Syntax & Example**
```js
// Selecting all <ul> -> <li> elements
let ulLiElement = document.querySelectorAll("ul li");
console.log(ulLiElement);

// Selecting <li> elements with class 'list-item' within <ul>
let ulListItemClass = document.querySelectorAll("ul li.list-item");
console.log(ulListItemClass);

// Setting the color of the last <li> element
ulLiElement[ulLiElement.length - 1].style.color = "red";

// Setting the text of the last <li> element
ulLiElement[ulLiElement.length - 1].innerHTML = "Dynamic text change at runtime";
```

#### `querySelector` 

- selects the single i.e. first element

> **Syntax & Example**
```js
// Selecting the first <h1> element
let firstHeadingElement = document.querySelector("h1");
console.log(firstHeadingElement);

// Setting the text of the first <h1> element
firstHeadingElement.innerHTML = "This is the first heading element";

// Selecting the first element with the class 'list-item'
let firstListItemElement = document.querySelector(".list-item");
console.log(firstListItemElement);

// Setting the text of the first element with the class 'list-item'
firstListItemElement.innerHTML = "This is the first list item element";
```

### JavaScript DOM CSS Styling

Using JavaScript we can also apply CSS style on HTML elements to change the visual look and feel specifications/presentations of HTML documents dynamically/at run time. We can apply/set almost all the CSS styles for the elements like fonts, colors, margins, padding, borders, alignments, background images, width and height, position, and so on.

#### Naming Conventions of CSS Properties in JavaScript

- CSS properties like `font-size`, `background-image`, `text-decoration`, etc. contain `hyphens (-)` in names.
- In JavaScript `hyphens (-)` is a reserved operator (a minus sign), so it is impossible to write an expression with `hyphens (-)`, like: elem.style.font-size = "10px";
- In JavaScript the CSS property names with hyphens are converted to camel-cased style word (camelCasingNaming)
CSS properties such as `font-size`, `background-color`, and `border-left-style` become the corresponding DOM properties `fontSize`, `backgroundColor`, and `borderLeftStyle`, respectively.

#### Applying/Setting Inline Styles on Elements

- In HTML, inline styles are applied directly to the specific HTML element using the `style` attribute, e.g., `<element style="color:red;">`.
- In JavaScript, the `style` property is used to get or set the inline style of an element, e.g., `elem.style.color = 'red';`.

> **Syntax & Example** 
```javascript
// Selecting the element with the ID 'mainHeadingText'
let mainHeadingElement = document.getElementById("mainHeadingText");

// Setting CSS styles inline
mainHeadingElement.style.padding = "5px";
mainHeadingElement.style.backgroundColor = "pink";
mainHeadingElement.style.color = "blue";
mainHeadingElement.style.border = "5px solid #999999";
```

#### Retrieving/Getting CSS Styles details from Elements

- We can get the styles applied to the HTML elements using the `style` property.
- The `style` property only returns the style rules set in the element's style attribute, not those applied through internal/embedded style sheets or external style sheets.
- To get the values of all CSS properties that actually render an element, we can use the `window.getComputedStyle()` method.

> **Syntax & Example**
```js
// Selecting the element with the ID 'mainHeadingText'
let mainHeadingElement = document.getElementById("mainHeadingText");

// Setting CSS styles inline
mainHeadingElement.style.padding = "5px";
mainHeadingElement.style.backgroundColor = "pink";

// Logging the inline CSS styles
console.log("mainHeadingElement.style.padding:", mainHeadingElement.style.padding);
console.log("mainHeadingElement.style.backgroundColor:", mainHeadingElement.style.backgroundColor);

// Getting computed style information from internal/embedded style sheets
var cssStyles = window.getComputedStyle(mainHeadingElement);
console.log("Internal style - color:", cssStyles.color);
console.log("Internal style - border:", cssStyles.border);
```

#### Applying/Adding CSS Classes to Elements - className

- We can also get or set CSS classes to the HTML elements using the `className` property.
- Since `class` is a reserved word in JavaScript, the `className` property is used to access and modify the value of the HTML class attribute.

> **Syntax & Example**
```js
// Selecting the element with the ID 'mainHeadingText'
let mainHeadingElement = document.getElementById("mainHeadingText");

// Removing old classes and applying the 'bg-color' class
mainHeadingElement.className = "bg-color";

// Applying the 'border' class
mainHeadingElement.className += " border";
```

#### Applying/Adding CSS Classes to Elements - classList

- Using the `classList` property is much easier and better for getting, setting, or removing CSS classes from an element.
- The `classList` property is supported in all major browsers, except Internet Explorer before version 10.

> **Syntax & Example** 
```js
// Selecting the element with the ID 'mainHeadingText'
let mainHeadingElement = document.getElementById("mainHeadingText");

// Applying the CSS class 'heading-text' using classList
mainHeadingElement.classList.add("heading-text");

// Applying multiple CSS classes 'border' and 'bg-color' using classList
mainHeadingElement.classList.add("border", "bg-color");

// Removing classes 'border' and 'bg-color' using classList
mainHeadingElement.classList.remove("border", "bg-color");

// Toggling the presence of the 'heading-text' class using classList
mainHeadingElement.classList.toggle("heading-text");

// Checking if the 'border' class exists and taking action accordingly
if (mainHeadingElement.classList.contains("border")) {
  alert("border class present");
} else {
  alert("NO border class present");
}
```

### JavaScript DOM HTML get set attributes

- An attribute in HTML `provides extra information` about the element and is applied within the start tag.
- An HTML attribute contains two fields: `name & value / key & value`.
- JavaScript provides several methods for adding, reading, or removing an HTML element's attribute, such as `setAttribute(), getAttribute(), removeAttribute()`.

#### Applying/Setting Attribute on Element

- The `setAttribute()` method is used to set an attribute on the specified element.
- If the attribute already exists on the element, the attribute value will be updated; otherwise, a new attribute is added with the specified name and value.

> **Syntax & Example** 
```js
// Selecting elements by their IDs
let mainHeadingElement = document.getElementById("mainHeadingText");
let clickButtonElement = document.getElementById("clickButton");
let linkTextElement = document.getElementById("linkText");

// Setting the class attribute to 'btn' for the main heading element
mainHeadingElement.setAttribute("class", "btn");

// Setting the 'disabled' attribute for the click button element
clickButtonElement.setAttribute("disabled", "");

// Removing the existing attribute value by setting the href attribute to blank/empty
linkTextElement.setAttribute("href", "");
```

#### Retrieving/Getting Attribute Value

- The `getAttribute()` method is used to get the current value of an attribute on the element.
- If the specified attribute is not present on the element, it will return `null`.

> **Syntax & Example** 
```js
// Selecting elements by their IDs
let mainHeadingElement = document.getElementById("mainHeadingText");
let clickButtonElement = document.getElementById("clickButton");
let linkTextElement = document.getElementById("linkText");

// Retrieving attribute values
let getAttrClass = mainHeadingElement.getAttribute("class");
console.log("getAttrClass:", getAttrClass);

let getAttrDisabled = clickButtonElement.getAttribute("disabled");
console.log("getAttrDisabled:", getAttrDisabled);

let getAttrHref = linkTextElement.getAttribute("href");
console.log("getAttrHref:", getAttrHref);
```

#### Removing Attributes from Elements

- The `removeAttribute()` method is used to remove an attribute from the specified element

> **Syntax & Example** 
```js
// Selecting elements by their IDs
let mainHeadingElement = document.getElementById("mainHeadingText");
let clickButtonElement = document.getElementById("clickButton");
let linkTextElement = document.getElementById("linkText");

// Removing the class attribute from the main heading element
mainHeadingElement.removeAttribute("class");

// Verifying if the class attribute has been removed
console.log("mainHeadingElement.getAttribute:", mainHeadingElement.getAttribute("class"));
console.log("mainHeadingElement.classList.contains:", mainHeadingElement.classList.contains("class"));

// Enabling the click button by removing the "disabled" attribute
clickButtonElement.removeAttribute("disabled");

// Removing the href attribute from the link text element
linkTextElement.removeAttribute("href");
```

#### Selecting document elements without selectors

> **Syntax & Example**
```js
- document.forms
  - document.forms[0] or use respective form element index
  - document.forms[0].id
  - document.forms[1].method
  - document.forms[1].action

- document.links
  - document.links[0]
  - document.links[0].className //class names as a string
  - document.links[1].classList[] // collection of classes

- document.images
  - document.images[0]

- document.scripts
  - document.scripts[0]
  - document.scripts[1].getAttribute("src");
```


## What's the next step?

- **Explore**: Explore more about JavaScript, its libraries like jQuery, frameworks like Angular, React, Vue, etc., and other related technologies.
- **Practice**: Practice is the key to success. The more you practice, the more you will learn and understand JavaScript. Try building small projects or applications using JavaScript.
- **Contribute**: Contribute to open-source projects, write articles, or create tutorials to share your knowledge with others.

#### Conclusion

Thank you for exploring my JavaScript notes. I hope you found them enjoyable and learned a lot from them.

Best of luck! 👍