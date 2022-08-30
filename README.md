# javaScript

## Comments

In javaScript codes we do use comments made with // (for one line/ line by line) and /* */ (multiple lines) to leave notes for ourselves or others who will later help us to figure out what the code does. Using the two types of comments will tell javaScript to ignore those lines. 

EX:<br>
~~~javascript
// Author: Any Medola <br>
/* imagine a text description by the author */
~~~

## Declare javaScript variables

In **computer science**, {c:red}data{/c} is anything that is meaningful for the computer. JvaScript has 8 different {c:red}data types{/c}: *undefined*, *null*, *boolean*, *string*, *symbol*, *bigint*, *number* and *object*.

Computers can distinguish between numbers({c:red}12{/c}) and sring({c:red}"12"{/c}), which are collections of characters so they can perfome mathematical operations on a number and not on a string.

Variables allow computers to store and manipulate data in dynamic way. Using a "label" to point to the data rather than using the data itself. Any of the eight types of data can be storage in variables.

We can create a variable in javaScipt by putting the keyword {c:red}var{/c} in front of it

EX:
~~~javascript
var ourName;
~~~

Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.

## Storing Values with the Assignment Operator

In JavaScript, you can store a value in a variable with the assignment operator (=).

EX:
~~~javascript
var myVar;
myVar = 5;
~~~

## Assigning the Value of One Variable to Another

After a value is assigned to a variable using the assignment operator, you can assign the value of that variable to another variable using the assignment operator.

EX:
~~~javascript
var myVar;
myVar = 5;
var myNum;
myNum = myVar;
~~~

## Initializing Variables with the Assignment Operator

It is common to initialize a variable to an initial value in the same line as it is declared.

EX:
~~~javascript
var myVar = 0;
~~~

## Declare String Variables

is called a string literal. A string literal, or string, is a series of zero or more characters enclosed in single or double quotes.

EX:
~~~javascript
var myName = "your name";
~~~

## Understanding Uninitialized Variables

When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a string of undefined.

EX: 
~~~javascript
// Only change code below this line
var a = 5;
var b = 10;
var c = "I am a";
// Only change code above this line

a = a + 1;
b = b + 5;
c = c + " String!";
~~~

