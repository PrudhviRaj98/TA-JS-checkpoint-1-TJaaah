1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

Ans: here it will return value

// second
function sum(a, b) {
  console.log(a + b);
}
```

Ans: it will print sum and return undefined

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Ans: first = 21;(value)

second = undefined;

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

Ans: it will only take two values from the arguments output is 36

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

Ans:yes we can store it will be called anonymous function or function expression

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

Ans: function sayHello(name){
  return name;
}

sayHello(`Hello Arya);

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

Ans: here it show error because username is not deifned .

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // erorr because username is not deifined 

showMessage(); // error because username is not deifned

alert(userName); // erorr because username is not deifined 
```

8. What is a Anonymous Function give example of three functions.

Ans:Anonymous function is nothing but assigning function to a variable  for example

let username = function (parameters){
  return.....;
}

username(arguments);

9. Can function declaration be a Anonymous Function? Explain

Ans: yes we can assign function to a variable 

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
Ans: examples

function sayHello{

}

function calc {

}
function create {

}
function check{
  
}
