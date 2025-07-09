<h1>
  <span class="prefix"></span>
  <span class="headline">Intro to Markdown Lab</span>
</h1>


![some alt text](https://images.unsplash.com/photo-1607706189992-eae578626c86?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8Y29kZXxlbnwwfHwwfHx8MA%3D%3D)

## About

This lab is designed with beginners in mind, making it a suitable starting point for those new to web development or text formatting. Markdown is a straightforward syntax used to format text. It's prevalent in multiple platforms like GitHub, forums, and even in data science notebooks. It allows you to create readable and well-structured documentation so you can concentrate on content rather than intricate formatting details.

## Content

- [Setup](./setup/README.md)
- [Exercise](./exercise/README.md)

## Deployed sites

🌐 [Live Example](https://pages.git.generalassemb.ly/modular-curriculum-all-courses/intro-to-markdown-lab-solution/live-solution/)


# Writing a Function in JavaScript

## In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
```javascript
const functionName = (params) => {
  // code to be executed
}
```
- **const:** const should be used whenever a function expression is assigned to a variable.
- **The function name:** The name you choose for the function.
- **Parameters:** Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
- **The arrow syntax:** Indicates that this will be a function.
- **The body:** The statements that make up the function itself. Surrounded by curly braces.

Example:

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

***Example:***

```javascript
greet('Alice'); // Outputs: Hello, Alice!
```

## 3. Return values

Functions can process data input and output a value using the *return* keyword.

***Example:*** 

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the MDN docs. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

# h1
## h2
### h3
#### h4
##### h5
###### h6

