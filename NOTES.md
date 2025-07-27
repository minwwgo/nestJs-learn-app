# JavaScript & TypeScript Notes

## let, const, var
- `let`: Block-scoped, can be updated.
- `const`: Block-scoped, cannot be reassigned.
- `var`: Function-scoped, legacy code.

## Block Scope
**Block scope** means a variable is only accessible within the curly braces `{}` where it is declared, such as inside a function, loop, or conditional statement.

**Example:**
```js
if (true) {
  let message = "Hello";
  console.log(message); // Works here
}
console.log(message); // Error: message is not defined
```

**Why is it important?**
- Prevents accidental changes to variables outside their intended area.
- Makes code safer and easier to understand.
- Avoids bugs caused by variable name conflicts.

**Summary:**  
Knowing about block scope helps you write cleaner, safer code by controlling where your variables can be used.

## Example: Add to Array
```js
let foods = ["rice", "noodle"];
foods.push("fish");
```

## Example: Update Object Property
```js
let user = { name: "Ko Ko", age: 25 };
user.age = 30;
```