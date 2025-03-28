# 🏷️ **JavaScript Variables**

In JavaScript, variables are used to store data that can be manipulated and retrieved later. Variables act as containers for values.

---

## 🔍 **Why Variables?**
- Store data values for reuse.
- Improve code readability and maintainability.
- Enable dynamic and interactive programming.

---

## 🏗️ **Declaration of Variables**
JavaScript provides three keywords to declare variables:

1. **var** — Function-scoped, can be redeclared.
2. **let** — Block-scoped, cannot be redeclared.
3. **const** — Block-scoped, cannot be redeclared or reassigned.

```javascript
// Using var
var name = "John";

// Using let
let age = 25;

// Using const
const country = "India";
```

---

## ⚙️ **Variable Rules**
- Variable names must start with a letter, $ or _.
- Cannot be a reserved keyword.
- Are case-sensitive.

```javascript
let firstName = "Alice";  // Valid
let 1stUser = "Bob";       // Invalid (starts with a number)
```

---

## 🏷️ **Types of Variables**

Variables in JavaScript can store different data types:

1. **String** — Textual data.
2. **Number** — Numeric values.
3. **Boolean** — true or false.
4. **Undefined** — Variable declared but not assigned a value.
5. **Null** — Intentionally empty value.
6. **Object** — Collection of key-value pairs.
7. **Symbol** — Unique identifier.

```javascript
let str = "Hello";              // String
let num = 42;                    // Number
let isActive = true;             // Boolean
let user;                        // Undefined
let empty = null;                // Null
let person = {name: "Sam"};     // Object
```

---

## 🛑 **Difference Between var, let, and const**

| Feature          | var            | let            | const          |
|------------------|----------------|----------------|--------------- |
| Scope            | Function       | Block          | Block          |
| Redeclaration    | ✅ Yes          | 🚫 No          | 🚫 No      
| Reassignment     | ✅ Yes          | ✅ Yes         | 🚫 No        
| Hoisting         | ✅ Yes          | 🚫 No          | 🚫 No        

---

## 🛠️ **Examples**

```javascript
// var example
var city = "Paris";
var city = "London";  // Redeclaration allowed
console.log(city);     // Output: London

// let example
let score = 10;
// let score = 20;    // Error: Cannot redeclare
score = 20;           // Reassignment allowed
console.log(score);   // Output: 20

// const example
const PI = 3.14;
// PI = 3.15;         // Error: Cannot reassign
```

---

## 📣 **Conclusion**
- Use **let** for variables that change.
- Use **const** for constants that never change.
- Avoid **var** to prevent scoping issues.
