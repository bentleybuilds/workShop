## Hack Reactor - JavaScript 201 Practice Problems

Welcome hacker in training! For this class, we will be working on the basics of arrays, objects, and iteration in JavaScript. 

This set of exercises uses arrays, objects, some methods, dot notation and bracket notation, as well as loops.

Hint: In JavaScript, to create a comment, just put two slashes "//" at he beginning of a line. Comments are a helpful note taking and organization technique! You will see comments used throughout this repo.

Before getting started, make sure that you have a JavaScript console open (like repl.it), so you can complete these exercises.
 
#### Part 1: Arrays in JavaScript 


Step 1: Declare a variable called colorArray and set it to an empty array.

Step 2: Re-assign colorArray to an array that has two elements in it. A string with the value: Black, and a string with the value: White. Use console.log to log colorArray to the console.

Step 3: Log the length of colorArray.

Step 4: Consider what: 

```JavaScript
console.log(colors[colors.length])
```
will log to the console?

Array Methods: the following expressions illustrate some of the basic methods used to manipulate arrays.

Use the following methods to alter an colorArray: .push, .pop, .shift, .unshift.

Step 5: Add 'Orange' to the beginning of colorArray.

Step 6: Add 'Purple' and 'Green' to the end of the sizes array.   

Step 7: Consider what: 

```JavaScript
console.log(colors[3])
```
will log to the console?

Step 8: Using .unshift and .pop, return colorArray to:
```JavaScript
['Black','White']
```


#### Part 2: Iterating Over Arrays

While arrays are used to store data, as a developer, you will often need to access and interact with each element in an array.

The most common way is through iteration using loops.

``` JavaScript
//Iterating is used for more than just listing elements, you will often want to modify each element in an array. 

var toBeDoubled = [1, 2, 5, 7, 4]
//Log each number doubled.
```

```JavaScript

// Can you count down in an array? Log the numbers in seconds, starting with 10.
var seconds = ['zero','one','two','three','four','five','six','seven','eight','nine','ten']
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
var user = [
    userName: 'Jessica',
    userAge: 32
]
```
```JavaScript
var eyes = {
    "color": "blue"
}
```
```JavaScript
var computer = {
    model: "Omen",
    make: HP,
    size: 17,
}
```
```JavaScript
//Consider the object myCar.  

var myCar = {
    make: 'Ford',
    model: 'Taurus',
    color: 'Silver'
}


// can you log a string that reads: 
// "My car is a [color] [make] [model]" 
// by accessing these properties from the object?

// Add the property [year] and set it to 1995, without redeclaring the object.

```

#### Part 4: Iterating Over Objects in JavaScript

Objects do not have length and their properties are not in order. Yet sometimes we still want to access each property.


Consider the object customerOrder
```JavaScript
var customerOrder = {
    customerName: 'Jeff',
    orderedItem: 'Blanket',
    size: 'Extra Large',
    cost: 68
}
```
Step 1: Declare a variable named "orderDetails" and set it to an empty array.

Step 2: Use a "For in" loop to populate orderDetails with each value.
