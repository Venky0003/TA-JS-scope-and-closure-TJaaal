1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function(marks, total) {
  return (marks * 100) /total;
}

let percentage = function calcPercentage(marks,total) {
  return (marks * 100) /total;
}
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

let percentage = (marks,total)=>(marks * 100)/total
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer function Declaration

```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
//  answer function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
//  answer function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
//  answer function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;
//  answer function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
// function defination can be converted in to an function expression because function is an object and objects can be stored in variable
example
```js
let fullName = function (firstName,lastName) {
  return `${firstName} ${lastName}`;
}
```

4. Why is a function call an expression in JavaScript?
// a function call expression is used to perform specified task with provided arguments
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer valid add function is taking two parameters and its executing when we call  five
five = add; // Answer valid five has been assigned the function of add
five = five(10, 11); // Answer valid it is assigned with parameters 10 and 11 it will give the result
five = function () {
  return 'Hello';
}; // Answer now five has assigned function expression with no arguments but with the string it will return string "Hello" on call
```

6. What is the difference between function definition and function call? Explain with an example.
//function defination is which defines the function to perform specific tasks with arguments but it does not execute or run.
//function call is when the function runs and gives you the result.
```js
function add(a,b) {
  return a+b;
} //this is function definattion 
add(5,3)// this call to execute function
```
7. What is the similarities between function definition and function call?
//In function defination it's all the procedure to acheieve particular task and using function call the task can run the function and will achieve the task 
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid as function is object by adding the property user will work
```

9. What is higher order function explain with an example.
// a higher order function that takes one more function as an arguments and results function as a result 
```js
function add(num1) {
  return function (num2) {
    return num1 + num2
  }
}
let adding = add(20);
console.log(adding(15));
```

10. Explain what is callback function. Why you can pass a function inside a function?
// a callback function is passed as an argument in another function to be called back when needed and the function that accepts another function as an argument is higher order function.
