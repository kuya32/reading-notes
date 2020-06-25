# Read: 07 - Programming with JavaScript

## How javascript makes web pages more interactive

- Access content
- Modify content
- Program rules
- React to events

## Writing a script

- Define the goal
- Design the script
- Code each step

## A script is a series of instructions that the computer can follow in order to achieve goals

## Computer approach task in different ways, so instruction is needed

## Expressions - evaluates into (results in) a single value. Broadly speaking there are two types of expressions

- var color = ‘beige’;
- var area = 3 * 2

## Operators - allow programmers to create a single value from one or more values

- Assignment operators
    - color = ‘beige’;
- Arithmetic operators
    - area = 3 * 2;
- String operator
    - greeting = “Hi” + “Molly”;
- Comparison operator
    - buy = 3 > 5;
- Logical operator
    - buy = (5 > 3) && (2 < 4);

## Other operators

- Increment (++) - adds one to the current number
    - i = 10; i ++;
        - 11
- Decrement (--) - subtracts one from the current number
    - i = 10; i --;
        - 9
- Modulus (%) - divides two values and returns the remainder
    - 10 % 3
        - 1

## Mixing numbers and strings together
    var number;
    var street = “Ivy Road”;
    var add = number + street;

        - Result: “12 Ivy Road”

### Pg. 79 shows Javascript within HTML

## Functions - group a series of statements together to perform a specific task

## To write a function, give it a name and then write the statements needed to achieve its task inside the curly braces

    Function sayHello() {
	    document.write(“Hello!”);
    }

### Call a function by stating function name

    sayHello();

## Declaring functions that need information

- Parameters inside the function act as variables

### Parameters vs Arguments

- Parameters
    - Inside the curly braces of the function, those words act like the variable
- Arguments
    - Values that you pass into the code (the information it needs too calculate the code block)
### Return 

- Calls the result of the function

[Back to Main](README.md)