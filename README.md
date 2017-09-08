# js-questions
Questions from 'Learning Javascript from Scratch'  an email course from Zell Liew

## Baby Phase

### What are the 5 primitive types in JS (six with ES6)?

String, Number, Null, Undefined, Boolean, (Symbol)

### How do you declare and assign variables in JS?

`var thing;` to declare a variable.

`var thing = 'my thing';` to assign a value to a variable. 

JS is weakly typed so you don't need to declare a type when setting variables (e.g. Number).

### What's the difference between var, const and let?

`var` is function scoped. If you declare a variable using `var` inside a function then it is accessible from anywhere in that function no matter how many sub-blocks it contains.

`const` is block scoped. A variable declared with `const` will only be accessible within the block it is defined in. Variables declared with `const` cannot be assigned a new value once set.

`let` is block scoped. A variable declared with `let` will only be accessible within the block it is defined in. Unlike `const`, variables declared with `let` can be changed later if needed.

### What do each of these operators do? `+ - * / %` 

Add, Minus, Multiply, Divide and Modulus (the remainder of a division)

### What do each of these operators do? `=== !== > >= < <=`

Strictly equal to, not strictly equal to, greater than, greater than and equal to, less than, less than and equal to.

The `===` and `!==` compare both the value and the type of two things whereas `==` and `!=` just compare the values. So for example:

`1 == '1' // true`

`1 === '1' // false`

### How do you use the following conditionals? `if, if else, else`

`if, if else and if` allow you to run a different block of code depending on if a specified condition is true or not. For example:

`var numApples = 5;
if( numApples === 0 ){
// do this
} else if ( numApples < 5) {
// do this
} else {
// do this
}

### How do you use a for loop?

### What is an array?

- How do you put values in an array?
- How do you get values out of an array?
- How do you remove a value from an array?
- How do you loop through every value of an array?

### What is an object?

- How do you put values in an object?
- How do you get values out of an object?
- How do you remove a value from an object?
- How do you loop through every value of an object?
