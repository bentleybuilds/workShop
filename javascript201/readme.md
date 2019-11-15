## Hack Reactor - JavaScript 201 Practice Problems

Welcome hacker in training! For this class, we will be working on the basics of arrays, objects, and iteration in JavaScript. 

This set of exercises uses arrays, objects, some methods, dot notation and bracket notation, as well as loops.

Hint: In JavaScript, to create a comment, just put two slashes "//" at he beginning of a line. Comments are a helpful note taking and organization technique! You will see comments used throughout this repo.

Before getting started, make sure that you have a JavaScript console open (like repl.it), so you can complete these exercises.
 
#### Part 1: Arrays in JavaScript 

Copy the following set of expressions into a REPL or directly into your Chrome console.

```JavaScript
// Declare an array
var colors = ['black', 'white', 'red', 'blue', 'yellow']

// Find the length of the array
colors.length

// What will colors[5] log to the console?
colors[5]
```

Array Methods: the following expressions illustrate some of the basic methods used to manipulate arrays.

// Use the following methods to alter an array: .push, .pop, .shift, .unshift .

```JavaScript
var sizes = ['small', 'medium', 'large']
// Add 'extra small' to the beginning of the sizes array

// Add 'extra large' to the end of the sizes array.   

// Change the sizes array back to the original content

``` 

#### Part 2: Iterating Over Arrays

While arrays are used to store data, as a developer, you will often need to access and interact with each element in an array.

The most common way is through iteration using loops.

```JavaScript

// Can you count down in an array? Log the numbers in seconds, starting with 10.
var seconds = ['zero','one','two','three','four','five','six','seven','eight','nine',ten']
```
``` JavaScript
//Iterating is used for than just listing elements, you will often want to modify these elements. 

var toBeDoubled = [1, 2, 5, 7, 4]
//Log each number doubled.
```
#### Part 3: Objects in JavaScript

While arrays are stored to use data, objects store data in such a way that meaning can be interpreted based on the key a value is assigned to.

```JavaScript
//Create variable named me set to an object with the values firstName, lastName, and hobbies. 
//Consider the data types that will need to be used for each value.
```

Consider each of the following objects. 
Can you correct the syntax?

```JavaScript
[
    name: 'Jeff',
    age: 34
]
```
```JavaScript
{
    "color": "blue"
}
```
```JavaScript
{
    model: "Omen",
    make: "HP",
    size: 17,
}
```
```JavaScript
//Consider the object myCar.  

var myCar = {
    make: 'Nissan',
    model: 'X-Terra',
    color: 'Green'
}


// can you log a string that reads: 
// "My car is a [color] [make] [model]" 
// by accessing these properties from the object?

// Add the property [year] and set it to 2005, without redeclaring the object.

```

#### Part 4: Iterating Over Objects in JavaScript

Objects do not have length and their properties are not in order. Yet sometimes we still want to access each property.

```JavaScript
// Consider the object myOrder

var myOrder = {
    customer: 'Jeff',
    size: 'tall',
    drink: 'Pumpkin Spice Latte'
}

//log the order details.
