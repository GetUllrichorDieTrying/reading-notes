# Code Fellows 102

## Class 8: Loops and Operators

### Assignment Operators

- An assignment opertor assigns a value to its left operand based on the value of its right operand.

| Name                            | Shorthand operator | Meaning          |
|---------------------------------|--------------------|------------------|
| Assignment                      | x = f()            | x = f()          |
| Addition assignment             | x += f()           | x = x + f()      |
| Subtraction assignment          | x -= f()           | x = x - f()      |
| Multiplication assignment       | x *= f()           | x = x * f()      |
| Division assignment             | x /= f()           | x = x / f()      |
| Remainder assignment            | x %= f()           | x = x % f()      |
| Exponentiation assignment       | x **= f()          | x = x ** f()     |
| Left shift assignment           | x <<= f()          | x = x << f()     |
| Right shift assignment          | x >>= f()          | x = x >> f()     |
| Unsigned right shift assignment | x >>>= f()         | x = x >>> f()    |
| Bitwise AND assignment          | x &= f()           | x = x & f()      |
| Bitwise XOR assignment          | x ^= f()           | x = x ^ f()      |
| Bitwise OR assignment           | x \|= f()          | x = x \| f()     |
| Logical AND assignment          | x &&= f()          | x && (x = f())   |
| Logical OR assignment           | x \|\|= f()        | x \|\| (x = f()) |
| Logical nullish assignment      | x ??= f()          | x ?? (x = f())   |

### Comparison Operators

- A comparison operator compares its operands and returns a logical value based on whether the comparison is true.
- The operands can be numerical, string, logical, or object values.

- **List of Comparison Operators**

  - Equal `==`
  - Not equal `!=`
  - Strict equal `===`
  - Strict not equal `!==`
  - Greater than `>`
  - Greater than or equal `>=`
  - Less than `<`
  - Less than or equal `<=`

### Loops

- Loops offer an easy way to do something repeadtly.
- Various loop mechanisms offer different ways to determine the start and end points of the loop.

### Loop `for` Statement

- A `for` statement loops until a specified condition is evaluated to be false.

- Example:

        for ([initialExpression]; [conditionExpression]; [incrementExpression])
            statement

1. The initializing expression `initialExpression`, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

2. The `conditionExpression` expression is evaluated. If the value of `conditionExpression` is true, the loop statements execute. If the value of `condition` is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)

3. The `statement` executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.

4. If present, the update expression `incrementExpression` is executed.

5. Control returns to Step 2.

### Loop While Statement

- A `while` statement loops until a specified condition is evaluated to be false.

- Example

        while (condition)
            statement

- If the `condition` becomes `false`, `statement` within the loop stops executing and control passes to the statement following the loop.

- The condition test occurs before `statement` in the loop is executed. If the condition returns `true`, `statement` is executed and the `condition` is tested again. If the condition returns `false`, execution stops, and control is passed to the statement following `while`.

- To execute multiple statements, use a block statement `({ ... })` to group those statements.

### Reference

[EXPRESSIONS AND OPERATORS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

[LOOPS AND ITERATION](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

Note: Some of these lists are direct quotes from the links referenced above. The instructions are explicit.
