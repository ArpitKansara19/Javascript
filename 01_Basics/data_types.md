# \ud83d\udcca **JavaScript Data Types**

---

## \ud83d\udd0d **What are Data Types?**  
Data types define the kind of data a variable can hold in JavaScript. It helps determine how memory is allocated and what operations can be performed.

---

## \ud83c\udff7\ufe0f **Two Categories of Data Types**  

1. **Primitive Data Types** (Stored by **Value**)  
2. **Reference Data Types** (Stored by **Reference**)  

---

## 1\u20e3 **Primitive Data Types**  
These are immutable and store simple values.  

| **Type**        | **Description**                         | **Example**                                 |
|-----------------|-----------------------------------------|---------------------------------------------|
| **String**      | Represents text or sequence of characters. | `"Hello, World"` |
| **Number**      | Represents both integer and floating-point numbers. | `42`, `3.14` |
| **Boolean**     | Represents true or false values. | `true`, `false` |
| **Null**        | Represents the intentional absence of value. | `let x = null;` |
| **Undefined**   | Represents a variable declared but not assigned a value. | `let y;` |
| **Symbol**      | Represents a unique identifier. | `Symbol('id')` |
| **BigInt**      | Represents integers larger than 2^53 - 1. | `9007199254740991n` |

---

## 2\u20e3 **Reference Data Types**  
These are mutable and store complex data structures.  

| **Type**        | **Description**                         | **Example**                                 |
|-----------------|-----------------------------------------|---------------------------------------------|
| **Object**      | Collection of key-value pairs. | `{ name: 'John', age: 25 }` |
| **Array**       | Ordered list of values. | `[1, 2, 3, 4]` |
| **Function**    | Block of code designed to perform a task. | `function greet() {}` |

---

## \ud83d\udee1\ufe0f **How to Check Data Type?**  
You can check the data type of any variable using the `typeof` operator.

```javascript
console.log(typeof "Hello");      // "string"
console.log(typeof 42);           // "number"
console.log(typeof true);         // "boolean"
console.log(typeof undefined);    // "undefined"
console.log(typeof {a: 1});       // "object"
console.log(typeof null);         // "object" (This is a known JavaScript bug)
console.log(typeof Symbol());     // "symbol"
console.log(typeof BigInt(123));  // "bigint"
```

---

## \ud83d\udee9 **Important Points to Remember**  
- `null` is considered an object due to legacy reasons.
- `undefined` means a variable is declared but not initialized.
- JavaScript is dynamically typed, meaning you don’t need to define the data type.