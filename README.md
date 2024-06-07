# Writing a Function in JavaScript

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. __Basic syntax__
```javascript
const functionName = (params) => {
  // code to be executed
}
```
* __const__: const should be used whenever a function expression is assigned to a variable.
* __The function name__: The name you choose for the function.
* __Parameters__: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* __The arrow syntax__: Indicates that this will be a function.
* __The body__: The statements that make up the function itself. Surrounded by curly braces.

_____Example_____:
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. __Calling a function__

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

_____Example_____:
```javascript
greet('Alice'); // Outputs: Hello, Alice!
```
## 3. Return values

Functions can process data input and output a value using the _return_ keyword.

___Example___: 
```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs. 
[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

<!-- 
1. Headers

# h1
## h2
### h3
#### h4
##### h5
###### h6

2. Text Styles

This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.

This text is ***bold and italicized***. This text is also ___bold and italicized___.

3. Creating a list 

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

4. Code Snippets

Use the `console.log()` function to print values to the console.

very important:
```javascript
const printItem = (item) => {
  console.log(item);
}
```
const printItem = (item) => {
  console.log(item);
}

5. Adding Links

[Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/

6.Blockquotes

> This is a blockquote.

7. Adding images

![some alt text](www.url_to_an_image.com/image)

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

![Computer with Code](/modular-curriculum-all-courses/intro-to-markdown-lab/exercise/assets/james-harrison-unsplash.jpg)

![Banner](https://images.unsplash.com/photo-1717479472303-e09bc657578e?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8)

For downloaded images:
![some alt text](./the-name-of-my-image.jpg)

8.Extended Syntax

| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~.  -->
