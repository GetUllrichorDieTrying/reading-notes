# Code Fellows 102

## Class 6: JavaScript

### Basics

- JavaScript is lightweight, interpreted, or just-in-time compiled programming language with first-class functions. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

### JavaScript Variables

#### 4 Ways to declare a variable in JavaScript

- Using `var`
- Using `let`
- Using `const`
- Using nothing
- **Variables are containers for storing data.**

#### When to use `const`?

- Rule of thumb: Always declare variables as `const`
- If I think the variables can change: use `let`

#### Identifiers

- JavaScript **variables** must be **identified** with **unique names** called **identifiers.**

#### The Assignment Operator

- Equal sign `=` is an "assignment" operator, not an "equal to" operator.
- `==` is the "equal to" operator.

#### Data Types

- Javascript Variables can hold numbers and text values.
- Text values are called strings in programming.
- Strings are written inside double or single quotes. Numbers are written without quotes.

#### Declaring Variables

- Declare varaible using var or let.

         var carName;
- After declaration, assign a value to the variable.

        carName = "Volvo";
- Alternatively, you can assign a value to a variable when it is declared.

        let carName = "Volvo";

**Note: It's a good programming practice to declare all variables at the beginning of a script.**

#### You can define many variables in one statment

        let person = "John Doe", carName = "Volvo", price = 200;

#### Value = undefined

- The variable carName will have the value undefined after the execution of this statement:

        let carName;

#### Re-Declared variables do not lose their value

        var carName = "Volvo";
        var carName;

### Reference

- [JavaScript MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Input Output in plain JavaScript](https://code-maven.com/input-output-in-plain-javascript)
- [JavaScript Variables](https://www.w3schools.com/js/js_variables.asp)
