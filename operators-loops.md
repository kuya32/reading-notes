# Read: 08 - Operators and Loops

## Comparison operators and how they relate to Booleans (true or false)

- Is equal to (==)
- Is not equal to (!=)
- Greater than (>)
- Less than (<)
- Strict equal to (===)
- Strict not equal to (!==)
- Greater than or equal to (>=)
- Less than or equal to (<=)

## Logical operators - comparison operators usually return single values of true and false

- Logical and (&&)
    - ( (2 < 5) && (3 >= 2) )
- Logical or (||)
    - ( (2 < 5) || (2 < 1) )
- Logical not (!)
    - ! (2 < 1)

## Loops

- Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false.

## Three common types of loops:

- For
- While
- Do while

## For Loop is made up of three statements

- Initialization
    - var i = 0;
- Condition
    - i < 10;
- Update
    - i++
- Put them all together:
    - for (var i = 0; i < 10; i++) {Some other function that runs it through}

## While loops

    var i = 1
    While ( i < 15) {
	    Do something;
	    i++;
    }

[Back to Main](README.md)