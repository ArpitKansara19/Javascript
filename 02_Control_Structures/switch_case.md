# Creating the switch_case.md file with the provided content

md_content = """
# Switch Case Statement in JavaScript

## Introduction
The `switch` statement in JavaScript is used to perform different actions based on different conditions. It is useful when you need to compare a variable against multiple possible values.

## Syntax
```javascript
switch(expression) {
    case value1:
        // Code to execute if expression === value1
        break;
    case value2:
        // Code to execute if expression === value2
        break;
    default:
        // Code to execute if none of the cases match
}

Example 1: Day of the Week

let day = 3;

switch(day) {
    case 1:
        console.log("Monday");
        break;
    case 2:
        console.log("Tuesday");
        break;
    case 3:
        console.log("Wednesday");
        break;
    case 4:
        console.log("Thursday");
        break;
    case 5:
        console.log("Friday");
        break;
    case 6:
        console.log("Saturday");
        break;
    case 7:
        console.log("Sunday");
        break;
    default:
        console.log("Invalid day");
}

Example 2: Calculator using Switch Case

let a = 10;
let b = 5;
let operator = "+";

switch(operator) {
    case "+":
        console.log("Addition: " + (a + b));
        break;
    case "-":
        console.log("Subtraction: " + (a - b));
        break;
    case "*":
        console.log("Multiplication: " + (a * b));
        break;
    case "/":
        console.log("Division: " + (a / b));
        break;
    default:
        console.log("Invalid operator");
}

Important Points
The break statement prevents the execution from falling through to the next case.

The default case is executed when none of the cases match.

Without break, the code continues to the next case even if a match is found.