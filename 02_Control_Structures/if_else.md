# If-Else Statement in JavaScript

## Introduction
The `if-else` statement in JavaScript is used for decision-making. It allows the execution of different blocks of code based on certain conditions.

## Syntax
```javascript
if (condition) {
    // Code to execute if the condition is true
} else {
    // Code to execute if the condition is false
}


Example 1: Checking Age for Voting Eligibility

let age = 18;

if (age >= 18) {
    console.log("You are eligible to vote.");
} else {
    console.log("You are not eligible to vote.");
}


Example 2: Checking Even or Odd Number

let number = 10;

if (number % 2 === 0) {
    console.log("The number is even.");
} else {
    console.log("The number is odd.");
}


Nested If-Else

let marks = 85;

if (marks >= 90) {
    console.log("Grade: A");
} else if (marks >= 75) {
    console.log("Grade: B");
} else if (marks >= 50) {
    console.log("Grade: C");
} else {
    console.log("Grade: F");
}

Ternary Operator (Shorter If-Else)
The ternary operator provides a shorter way to write if-else.

let num = 5;
let result = (num > 0) ? "Positive Number" : "Negative Number";
console.log(result);


Conclusion
The if statement executes a block of code if the condition is true.

The else statement executes an alternative block if the condition is false.

Multiple conditions can be handled using else if.

The ternary operator (condition ? trueStatement : falseStatement) is a shorthand for if-else.

