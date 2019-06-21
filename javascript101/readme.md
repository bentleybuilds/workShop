
## Hack Reactor - Javascript 101 Practice Problems

Welcome hacker in training! For this class, we will be working on the basics of types, variables, operators and functions in Javascript. If you feel you've already mastered these concepts, dive in to javascript201! 

This set of exercises uses numbers, strings, arithmetic operators and comparison operators, as well as function syntax and the return keyword.


Hint: In Javascript, to create a comment, just put two slashes "//" at he beginning of a line. Comments are a helpful note taking and organization technique! You will see comments used throughout this repo.

 
#### Part 1: Types in Javascript 

Copy the following set of expressions into a REPL or directly into your Chrome console.

```
// Add two numbers together
22 + 4

// Add two strings together
'22' + '4'

// Multiply two numbers
3 * 3 
```

Type coercion: the following expressions illustrate some of the unexpected behaviors when we mix types and operators in Javascript. At certain times, Javascript will 'coerce' a value into a different type. 

// Before you run the following lines of code, make a guess what the output will be.

```
// Multiply two strings
'9' * '9'

// Divide a number by a string 
12 / "6"

// Add two numbers to a string
"number" + 15 + 3

// Add a string to two numbers
15 + 3 + "number"
```

#### Part 2: Variables in Javascript

Start by copying the below code 

```
var myFirstName
var myLastName = 'Cordova'

console.log(myFirstName)
console.log(myLastName)
```

1. Reassign the values of myFirstName and myLastName with your own first and last name 

2. Declare a variable called phoneNumber and assign it to a string of your phone number with dashes 


#### Part 3: Operators in Javascript 

```
// Order of operations: what will the output of the following expression be? 
(36 * 2 + 8 - 2) / 2 

// The number 9 is greater than the number 9.
9 > 9

// The number 9 is great than or equal to the number 9. 
9 >= 9

// The string of "9" is greater than the number 8
"9" > 8

// The number 9 loosely equals the string "9"
13 == "13"

// the number 0 loosely equals the boolean false
0 == false

// The number 13 strictly equals the string "13"
13 === "13"

// The string "hola" strictly equals the string "Hola"
"hola" === "Hola"
```

#### Part 4: Functions 

Write a function called multiple that takes two parameters (both numbers) and returns the product of those two numbers.

Write a function call fullName that takes 3 parameters, all strings, a first name, a middle name and a last name, and returns a full name with spaces in the correct place
- ex inputs: 'Cyntoia', 'Renee', 'Washington'
- output: 'Cyntoia Renee Washington' 