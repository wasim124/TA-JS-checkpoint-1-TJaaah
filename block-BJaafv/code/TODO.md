1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}

console. log() is a function used to print information to the console. return on the other hand is a call to pass some value back up to where the call was made.

```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();


'Hello, John'
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 Jhon

showMessage(); // Output 2 'Hello, John'

alert(userName); // Output 3 John
```

8. What is a Anonymous Function give example of three functions.

//An anonymous function is a function that was declared without any named identifier to refer to it. As such, an anonymous function is usually not accessible after its initial creation. eg.-

const addNum = function(num1,num2){
  num1+num2;
};

const fullName = (firstName, lastName) => `firstName + " " + lastName`;

9. Can function declaration be a Anonymous Function? Explain

// NO , becz we have to name the function 

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
