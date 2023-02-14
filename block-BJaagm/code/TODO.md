1. What does thread of execution means in JavaScript?
 javaScript engine takes code line by line and executes it this known as thread

2. Where the JavaScript code gets executed?
the JavaScript engine creates an global execution context this were the code gets executed in it

3. What does context means in Global Execution Context?
Global execution context is an environment/state where the code gets executed

4. When do you create a global execution context.
Glabal execution context is created when the JavaScript file starts to run first

5. Execution context consists of what all things?
it consits of code and memory and everything that helps in executing

6. What are the different types of execution context?
Global execution context
Function Execution context

7. When global and function execution context gets created?
when the JavScript file starts to run

8. Function execution gets created during function execution or while declaring a function.
Function Execution context gets created during function execution

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

`![](./img/image-1.jpg)`



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

`![](./img/image-2.jpg)`



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

`![](./img/image-3.jpg)`