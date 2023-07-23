# Statements & Expressions
## Exercise 1
How many statements there are in the following code example? List all of them.

```javascript
y = x * 42 - z;
```

## Exercise 2
How many expressions there are in the following code example? List all of them.

```javascript
y = x + 318;
```

## Exercise 3
How many statements and expressions there are in the following code example? List all of them.

```javascript
x = 2;
z = x / 659;
y = x - z;
```

## Exercise 4
How many statements and expressions there are in the following code example? List all of them.

```javascript
x = 6;
y = x / 2;
alert(y);
```

# Operators
## Exercise 5
In the following code example what would be printed to the console? Why?

```javascript
var x = 12;
console.log(x);
```

## Exercise 6
In the following code example what would be printed to the console? Why?

```javascript
var x = 2;
var a = 12;
x = a / 3;

console.log(x);
```

## Exercise 7
In the following code example what would be printed to the console? Why?

```javascript
x = 0;
x /= 3;
x += 17;
x -= 18;
x *= 2;

console.log(x);
```

## Exercise 8
In the following code example what would be printed to the console? Why?

```javascript
x += 24;
console.log(x);
```

## Exercise 9
In the following code example what would be printed to the console? Why?

```javascript
var x = 7;
x++;
x++;
x--;

console.log(x);
```

## Exercise 10
How many statements and expressions there are in the following code example? List all of them.

```javascript
var x = 0;
x++;
```

## Exercise 11
Which value does `x` have after execution of the following code?

```javascript
var x = 3;
x++;
x = x * 2;
x--;
```

# Types & Variables
## Exercise 12
Declare a variable `firstname` and initialize it with the value `'Alex'`.

## Exercise 13
Declare a variable `flower` and assign it the value `'rose'`. Declare a second variable `tree` and assign it the value `'maple'`.

## Exercise 14
In the following code example what is the type of the variable `a`? What about the variables `b` and `c`?

```javascript
var a = 13;
var b = "13";
var c = true;
```

## Exercise 15
In the following code example what is the type of the variables `b` and `c`? What would be printed to the console and why?

```javascript
var a = 74;
var b = String(a);
var c = a == b;

console.log(c);
```

## Exercise 16
Which value does `x` have after execution of the following code?

```javascript
var x = 'John';
var y = 'Doe';
var z = y;
y = x;
x = z;
```

## Exercise 17
How many statements and expressions there are in the following code example? List all of them.

```javascript
name = prompt("What is your name?");
alert("Hello " + name + "!");
```

## Exercise 18
Given that user has entered the following name: "John", write down what would exactly the alert say? What is the type of variable `name`?

```javascript
name = prompt("What is your name?");
alert("Hello " + name + "!");
```

## Exercise 19
In the following code example what would be printed to the console each time? Why?

```javascript
var battety = 15;

battery += 60;
console.log("Battery charged to " + battety + "%");

battery = 0;
battery += 5;
console.log("Battery charged to " + battery + "%");
```

## Exercise 20
In the following code example what would be printed to the console and why? What is the type of the variable `speed` after console output?

```javascript
const ADDITIONAL_ACCELERATION = 0.1;
var speed = 150;
var boost = 2;

speed = speed * boost;
speed += speed * ADDITIONAL_ACCELERATION;

speed += "km/s";

console.log("Current speed: " + speed);
```

## Exercise 21
Write the code that will swap the following variable values so that variable `a` holds the value of the variable `b`, and the variable `b` holds the value of the varable `a`. Print their values to the console.

```javascript
var a = 317;
var b = "Hey there!";
```

## Exercise 22
Solve the previous exercise using only one additional variable. 

## Exercise 23
Fix the following crappy code example so it works as intended.

```javascript
const name = prompt(What is your name?);
console.log("Provided name: " + "name");

name = "Dear " + name;
cosnole.log("Hello ' + name);
```

## Exercise 24
Which value does `x` have after execution of the following code?

```javascript
var x = 'Tic';
x = x + 'Tac';
x = x + x;
```

# Conditionals & Loops
## Exercise 25
In the following code example what would be printed to the console? Why?

```javascript
var coctails = 3;

if (coctails <= 3) {
    console.log('One more please!');
    coctails++;
}

console.log("I'd like to pay for my " + coctails + " coctails");
```

## Exercise 26
In the following code example what would be printed to the console? Why?

```javascript
var coctails = 4;
var stillHuman = coctails < 3;

if (stillHuman) {
    console.log('Can I have a bill please?');
} else {
    console.log("Gim'me ma bill n' take ma money or I'll sue you!");
}
```

# Functions & Scope
## Exercise 27
Define a function `hello` that returns `'Hello world!'`.

## Exercise 28
Define two functions. The first function `a` should return `'Hello a!'` and the second function `b` should return `'Hello b!'`.

## Exercise 29
1. Define a function `greet` returning the value `'Haydo!'`.
2. Declare a variable `salutation`. Call the function `greet` and assign the result of the call to the variable `salutation`.

## Exercise 30
Which value does `x` have after execution of the following code?

```javascript
function hello() {
  return 'Hi!';
}

var x = hello();
```

## Exercise 31
Write a function `echo` that returns the passed parameter. `echo('John')` should return `'John'` and `echo('CO2')` should return `'CO2'`.

## Exercise 32
Which value does `x` have after execution of the following code?

```javascript
function reply(phrase) {
  return phrase;
}

var x = reply('How do you do?');
```

## Exercise 33
Write a function `greet` having one parameter and returning `'Hello <parameter>!'`.

Example: `greet('Alex')` should return `'Hello Alex!'` and `greet('John')` should return `'Hello John!'`.

## Exercise 34
Which value does `x` have after execution of the following code?

```javascript
function whereIs(name) {
  return 'Where is ' + name + '?';
}

var x = whereIs('Jacky');
```

## Exercise 35
Which value does `x` have after execution of the following code?

```javascript
function hi(name) {
  return 'Hi ' + name + '!';
}

var h1 = hi('Selva');
var h2 = hi('Pola');
var x = h1 + ' ' + h2;
```

## Exercise 36
Write a function `log` that logs `'Hello Console!'`.

## Exercise 37
Write a function `log`, that takes a parameter and logs this parameter.

Example: `log('Ken Thompson')` should log `'Ken Thompson'`.

## Exercise 38
Write a function `shout` that takes a string and returns this string duplicated. In addition, the return should be logged.

Example: `shout('Fire')` should return `'FireFire'` and should log `'FireFire'`.

## Exercise 39
Which value does `x` have after execution of the following code?

```javascript
function double(name) {
  return name + ' and ' + name;
}

var x = double('Roy');
```

## Exercise 40
Write a function `add` that takes two numbers and returns their sum.

Example: `add(1, 2)` should return `3`.

## Exercise 41
Write a function `toFahrenheit` that converts a temperature from Celsius to Fahrenheit.

Example: `toFahrenheit(0)` should return `32`.

Hint: If C is the temperature in Celsius and F the temperature in Fahrenheit, the following applies: F = 1.8 * C + 32.

## Exercise 42
Write a function `nand` that takes two Boolean values. If both values are `true`, the result should be `false`. In the other cases the return should be `true`.

I.e.: The call `nand(true, true)` should return `false`. The calls `nand(true, false)`, `nand(false, true)` and `nand(false, false)` should return `true`.

## Exercise 43
Write a function `nor` that takes two Boolean values. If both values are `false`, the result should be `true`. In the other cases the return should be `false`.

I.e.: The call `nor(false, false)` should return `true`. The calls `nor(true, false)`, `nor(false, true)` and `nor(true, true)` should return `false`.
