1. Using loops take 10 inputs from user and find the average of all the numbers.

function input (total){
  let count = 0;
  let sum = 0;
  for( i = 0 ; i <= 10 ; i++ ){
    let value = +prompt(`enter 10 inputs`);
    sum = sum + i;
    count ++
  }
  let avg = sum / count;
  return avg;
}

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
Ans:println is not defined

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

function getEvenSum (max){
  max = 50;
  let count = 0;
  let sum = 0;
  for(let i = 0 ; i <= max ; i++){
    if(i % 2 == 0){
      sum = sum + i;
    }
  }
  return sum;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getOddSum (max){
  max = 10;
  let count = 0;
  let sum = 0;
  for(let i = 0 ; i <= max ; i++){
    if(i % 2 != 0){
      sum = sum + i;
    }
  }
  return sum;
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

function getProductOfDigits (num){
  let product = 1;
  if (num < 0){
    return `not a valid input`;
  }else {
    while(num != 0){
      product = product * (num / 10); 
    }
    return product;
  }
}
  

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // bigger than 5 because it num > 5 it executes if block
check(1); // smaller than 5 because it num <> 5 it executes else block
check(5); // 5 because 5 is == so condition is not defined in that case it will return num
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // Arya is equal to Arya in if block so it returns you are arya
getOutput('John'); // john is equal to john so it returns you are john
getOutput(); // it is just a calling a funtion in that case it will return the who are you
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // it will print you are Arya but it will also return who are you
getOutput('John'); // it will print you are john but it will also return who are you
getOutput(); // it will retrun who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Ans:yes we can give multiple return statements

example:function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

Ans: in for loop we need to know condition and how many time it needs to be iterated whereas in case of while loop only if we know condition then it is enough