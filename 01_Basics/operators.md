# ➕ **JavaScript Operators**

---

## 🔍 **What are Operators?**  
Operators in JavaScript are special symbols or keywords that perform operations on variables and values.

---

## 🏷️ **Types of Operators**

1. **Arithmetic Operators**  
2. **Assignment Operators**  
3. **Comparison Operators**  
4. **Logical Operators**  
5. **Bitwise Operators**  
6. **Ternary Operator**  
7. **Type Operators**

---

## ➗ **1. Arithmetic Operators**
Used for performing mathematical calculations.

| **Operator** | **Description**      | **Example**               |
|--------------|----------------------|---------------------------|
| +          | Addition              | 5 + 2 = 7               |
| -          | Subtraction           | 5 - 2 = 3               |
| *          | Multiplication        | 5 * 2 = 10              |
| /          | Division              | 5 / 2 = 2.5             |
| %          | Modulus (Remainder)   | 5 % 2 = 1               |
| ++         | Increment             | let a = 5; a++ = 6      |
| --         | Decrement             | let a = 5; a-- = 4      |

### 📁 **Example:**
```javascript
let a = 10;
let b = 3;
console.log(a + b); // 13
console.log(a - b); // 7
console.log(a * b); // 30
console.log(a / b); // 3.33
console.log(a % b); // 1
```

---

## 📝 **2. Assignment Operators**
Used to assign values to variables.

| **Operator** | **Example**     | **Equivalent To**        |
|--------------|----------------|--------------------------|
| =          | x = y         | x = y                  |
| +=         | x += y        | x = x + y              |
| -=         | x -= y        | x = x - y              |
| *=         | x *= y        | x = x * y              |
| /=         | x /= y        | x = x / y              |
| %=         | x %= y        | x = x % y              |

### 📁 **Example:**
```javascript
let x = 10;
x += 5;
console.log(x); // 15
```

---

## 🔍 **3. Comparison Operators**
Used to compare two values.

| **Operator** | **Description**       | **Example**               |
|--------------|-----------------------|---------------------------|
| ==         | Equal to               | 5 == '5' // true        |
| ===        | Strict equal to        | 5 === '5' // false      |
| !=         | Not equal to           | 5 != '5' // false       |
| !==        | Strict not equal       | 5 !== '5' // true       |
| >          | Greater than           | 5 > 3 // true           |
| <          | Less than              | 5 < 3 // false          |
| >=         | Greater than or equal  | 5 >= 5 // true          |
| <=         | Less than or equal     | 5 <= 5 // true          |

### 📁 **Example:**
```javascript
console.log(5 == '5');    // true
console.log(5 === '5');   // false
console.log(10 > 5);      // true
console.log(10 <= 10);    // true
```

---

## ⚙️ **4. Logical Operators**
Used to perform logical operations.

| **Operator** | **Description**       | **Example**               |
|--------------|-----------------------|---------------------------|
| &&         | Logical AND            | true && false // false  |
| (||)      | Logical OR             | true || false // true   |
| !          | Logical NOT            | !true // false          |

### 📁 **Example:**
```javascript
let isAdult = true;
let hasID = false;
console.log(isAdult && hasID); // false
console.log(isAdult || hasID); // true
console.log(!isAdult);         // false
```

---

## 🏁 **5. Bitwise Operators**
Used to perform bitwise operations.

| **Operator** | **Description**       | **Example**               |
|--------------|-----------------------|---------------------------|
| &          | AND                    | 5 & 1 // 1              |
| \|          | OR                     | 5 \| 1 // 5              |
| ^          | XOR                    | 5 ^ 1 // 4              |
| ~          | NOT                    | ~5 // -6                |
| <<         | Left Shift             | 5 << 1 // 10            |
| >>         | Right Shift            | 5 >> 1 // 2             |

### 📁 **Example:**
```javascript
console.log(5 & 1); // 1
console.log(5 | 1); // 5
console.log(5 ^ 1); // 4
```

---

## ❓ **6. Ternary Operator**
A shorthand for the if-else statement.

### 📁 **Example:**
```javascript
let age = 20;
let status = (age >= 18) ? 'Adult' : 'Minor';
console.log(status); // 'Adult'
```

---

## 🏷️ **7. Type Operators**
Used to determine the type of a variable or to create an object instance.

| **Operator** | **Description**           | **Example**                |
|--------------|---------------------------|----------------------------|
| typeof     | Returns the type of a variable | typeof 5 // 'number' |
| instanceof | Checks if an object is an instance of a class | obj instanceof Array |

### 📁 **Example:**
```javascript
console.log(typeof 'Hello'); // string
console.log([] instanceof Array); // true
```

---

## 🏁 **Important Points to Remember**
- Always use === instead of == for strict equality.
- The typeof null returns "object" due to a legacy bug.
- Bitwise operators are rarely used in high-level applications.
