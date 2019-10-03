
## Hack Reactor - JavaScript 101 Practice Problems

Welcome hacker in training! For this class, we will be working on the basics of types, variables, operators and functions in JavaScript. If you feel you've already mastered these concepts, dive in to javaScript201! 

This set of exercises uses numbers, strings, arithmetic operators and comparison operators, as well as function syntax and the return keyword.

Hint: In JavaScript, to create a comment, just put two slashes "//" at he beginning of a line. Comments are a helpful note taking and organization technique! You will see comments used throughout this repo.

Before getting started, make sure that you have a JavaScript console open (like repl.it), so you can complete these exercises.
 
#### Part 1: Types in JavaScript 

Copy the following set of expressions into a REPL or directly into your Chrome console.

```JavaScript
// Add two numbers together
22 + 4

// Add two strings together
'22' + '4'

// Multiply two numbers
3 * 3 
```

Type coercion: the following expressions illustrate some of the unexpected behaviors when we mix types and operators in JavaScript. At certain times, JavaScript will 'coerce' a value into a different type. 

// Before you run the following lines of code, make a guess what the output will be.

```JavaScript
// Multiply two strings
'9' * '9'

// Divide a number by a string 
12 / "6"

// Add two numbers to a string
"number" + 15 + 3

// Add a string to two numbers
15 + 3 + "number"
```

#### Part 2: Variables in JavaScript

Start by copying the code below into your repl, then add on to complete the numbered steps below.

```JavaScript
var myFirstName
var myLastName = 'Cordova'

console.log(myFirstName)
console.log(myLastName)
```

1. Reassign the value of myFirstName to a string of your first name.

2. Reassign the value of myLastName to a string of your own last name. 

2. Declare a variable called myMiddleName and assign it to a string of your middle name. 

3. Declare a variable called full name and assign it to the value of your whole name using the previously created variables for first, middle and last name. Don't forget the spaces! 
ex output: 'Estevan Guiellermo Consejo'


Copy the following code into your repl and fix each of the incorrect variable declarations in a console -- some are syntactically invalid, some disobey style guidelines, and some are just weird.

```JavaScript
var "animal" = "monkey"
var "monkey" = animal
var x= 15
var y =10
var var = "huh?"
var true = false
var isTenEven = 10 % 2 = 0
```

For each of the following code blocks, copy the code into a repl. Before you run the code, try to reason about what the value of x is supposed to be on the last line. Once you have arrived at a conclusion that you are comfortable with, check your answer. Was your hypothesis correct? If not, ensure that you understand why (talk with a classmate, or ask for help).

```JavaScript
var x = 5;
x + 10;
x; // => ???
```

```JavaScript
var x = 17;
x = (x + 1) / 2;
x * 4;
x; // => ???
```

```JavaScript
var x = 5;
var y = 20;
x = y;
y = y + 7;
x; // => ???
```

```JavaScript
var x = 10;
var y = 5;
x = (x * 4) - 3;
x + 17;
x = x + y;
x; // => ???
```

#### Part 3: Operators in JavaScript 
Copy the following lines of code into a repl. 

```JavaScript
// Order of operations: what will the output of the following expression be? 
(36 * 2 + 8 - 2) / 2 

// The number 9 is greater than the number 9.
9 > 9

// The number 9 is great than or equal to the number 9. 
9 >= 9

// The string of "9" is greater than the number 8
"9" > 8

// The number 13 loosely equals the string "13"
13 == "13"

// the number 0 loosely equals the boolean false
0 == false

// The number 13 strictly equals the string "13"
13 === "13"

// The string "hola" strictly equals the string "Hola"
"hola" === "Hola"
```

#### Part 4: Functions 

1. Write a function called multiple that takes two parameters (both numbers) and returns the product of those two numbers.

2. Write a function called fullName that takes 3 parameters, all strings, a first name, a middle name and a last name, and returns a full name with spaces in the correct place
- ex inputs: 'Cyntoia', 'Renee', 'Washington'
- output: 'Cyntoia Renee Washington' 

3. Write a function called greeting that takes a name and returns a personalized greeting. 
- ex input: 'Jade'
- ex output: 'Top of the mornin' Jade!'

4. Write a function called calculateTip that takes a total and a decimal between 0 and 1 and returns a string message showing the amount of tip owed. 
- ex input: 25, .2
- ex output: "The tip amount you owe is $5"
- hint: don't forget the dollar sign! 