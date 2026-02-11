## What is JavaScript?

JavaScript is a high-level, dynamic, and interpreted programming language mainly used to build interactive and dynamic web applications.

It allows developers to manipulate HTML and CSS, handle user events like clicks and form submissions, and communicate with servers using APIs.

Today, JavaScript is not limited to browsers only — it can also run on the server side using environments like Node.js.

## What is the role of the JavaScript Engine?

A JavaScript engine is responsible for executing JavaScript code.

It reads the code, parses it, converts it into machine code, and then executes it so that the browser or runtime can perform the required actions.

Different browsers have different JavaScript engines. For example, Chrome uses the V8 engine.

## How does JavaScript work internally?

Internally, the JavaScript engine first parses the code and creates an Abstract Syntax Tree (AST). Then it compiles the code into machine code using Just-In-Time (JIT) compilation and executes it. It also manages memory using garbage collection.

## What is Client-Side?

Client-side refers to everything that runs on the user's browser.

It is responsible for the user interface, design, and interactions like button clicks, form validation, and animations.

Technologies used on the client side include HTML, CSS, and JavaScript.

Simple Example:

When you click a button and a popup appears without refreshing the page — that is client-side processing.

## What is Server-Side?

Server-side refers to everything that runs on the server.

It is responsible for handling business logic, database operations, authentication, and sending responses back to the client.

Technologies used on the server side include Node.js, Python, Java, PHP, etc.

Simple Example:

When you log in to a website and your password is checked with the database — that is server-side processing.

## What are Variables?

Variables are containers used to store data in a program.

We use variables to store values like numbers, strings, or objects so that we can use and modify them later in the program.

Example:

```Javascript

let name = "Ashutosh";
let age = 21;

```
Here, name and age are variables that store values.

## What is the difference between var, let, and const?

var, let, and const are used to declare variables in JavaScript, but they behave differently in terms of scope and re-assignment.

### 1️. var

var is function-scoped and can be re-declared and updated.

It was used in older versions of JavaScript.

Example:

```Javascript

var x = 10;
var x = 20;   // Allowed

```

## 2️. let

let is block-scoped and can be updated but cannot be re-declared in the same scope.

Example:

```Javascript

let y = 10;
y = 20;       // Allowed
// let y = 30; Not allowed in same block

```
## 3. const

const is block-scoped and cannot be updated or re-declared.

It is used when the value should not change.

Example:

```Javascript

const z = 10;
// z = 20; Not allowed

```

## What are some important string operations in JS?

In JavaScript, strings are used to store text.

There are many built-in methods available to perform operations on strings.

### Some important string operations are:
### 1️. length
The length property is used to find the total number of characters in a string.

```Javascript

let name = "Ashutosh";
console.log(name.length);

Output:

8

```
### 2️. toUpperCase() and toLowerCase()

These methods are used to convert a string into uppercase or lowercase.

```Javascript

let text = "hello";
console.log(text.toUpperCase());
console.log(text.toLowerCase());

Output:

HELLO
hello

```

### 3️. trim()

The trim() method removes extra spaces 
from the beginning and end of a string.

```Javascript

let text = "  hello  ";
console.log(text.trim());

Output:

hello

```

### 4️. slice()

The slice() method extracts a part of a string.

```Javascript

let text = "JavaScript";
console.log(text.slice(0, 4));

Output:

Java

```
### 5. replace()

The replace() method replaces part of a string with another value.

``` Javascript

let text = "Hello World";
console.log(text.replace("World", "JS"));

Output:

Hello JS

```

### 6️. includes()

The includes() method checks whether a string contains a specific value.

```Javascript

let text = "JavaScript";
console.log(text.includes("Script"));

Output:

true

```

## What is DOM?

DOM stands for Document Object Model.
It is a programming interface for web documents.

The DOM represents an HTML document as a tree structure of objects, where each element becomes a node.

JavaScript uses the DOM to access, modify, add, or delete HTML elements dynamically.

Simple Example:

```Javascript

document.getElementById("demo").innerHTML = "Hello World";

```
This change happens using the DOM.

## What is the difference between HTML and DOM?

HTML is a markup language used to create the structure of a web page.

The DOM is the object representation of that HTML structure created by the browser, which allows JavaScript to interact with it.

