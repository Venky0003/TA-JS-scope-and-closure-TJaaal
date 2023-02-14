Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = 'Arya';
}
console.log(useranme); // output
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = 'Arya';
}
console.log(useranme); // output
```
In above code we are looking  for the variable `username`. There is no variable `username` in the global scope.the variable inside the curly brackets is using const and its a  block scoped and we cannot access it from outside.

The above code will throw an error `Reference Error username is not defined`.

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```
In above code we are looking  for the variable `username`. There is no variable `username` in the global scope.the variable inside the curly brackets is using let and its a block scoped and we cannot access it from outside.

The above code will throw an error `Reference Error username is not defined`.

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output
```
In above we are looking for variable named `username`.so the variable named `` username is used in the curly brackets using var which is not a block scope so we can acces it.

The above code will give `Arya` 

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  var username = 'Arya';
}
console.log(useranme); // output
```
In the above code we are looking for variable named `username`.but the variable `username` is been used twice both are global scope and been used different variable declarations let and var. so it will not be accessible

The above code will throw an error `Identifier 'username' has already been declared`

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
if (true) {
  let username = 'Arya';
}
console.log(useranme); // output
```
In the above code we are looking for the variable named `username`.There is a global scope variable `username` is available and is accesible.

The above code gives the result `John`

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = 'John';
function sayHello() {
  let username = 'Arya';
}
sayHello();
console.log(useranme); // output
```
In the above code we are looking for variable named `username`.There is vraiable `username` in the global scope.

The above code gives the result `John`.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```
In the above code we are looking for variable `i`.There is variable named `i`in the global scope.

The above gives the result ` 0 'First' `
                           ` 1 'First' `
                           ` 2 'First' `
                           ` 3 'First' `
                           ` 4 'First' `
                           ` 5 'First' `
                           ` 6 'First' `
                           ` 7 'First' `
                           ` 8 'First' `
                           ` 9 'First' `
                           ` 10 'Second' `


9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, 'First'); // output
}
console.log(i, 'Second'); // output
```
In the above code we are looking for variable named `i`.The variable named `i`is a block scope and will be accessed inside the block and not by global scope.

The above code gives the result for block scope  ` 0 'First' `
                                                 ` 1 'First' `
                                                 ` 2 'First' `
                                                 ` 3 'First' `
                                                 ` 4 'First' `
                                                 ` 5 'First' `
                                                 ` 6 'First' `
                                                 ` 7 'First' `
                                                ` 8 'First' `
                                                ` 9 'First' `

The above code throws an error in global scope `i is not defined`                                                

