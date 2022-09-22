# Day 4 cont

## Expressions, Operators and Loops

### Expressions and Operators

At a high level, an expression is a valid unit of code that resolves to a value. There are two types of expressions: those that have side effects (such as assigning values) and those that purely evaluate.

* The expression x = 7 is an example of the first type. This expression uses the = operator to assign the value seven to the variable x. The expression itself evaluates to 7.

* The expression 3 + 4 is an example of the second type. This expression uses the + operator to add 3 and 4 together and produces a value, 7.

### Assignment operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

### Comparison operators

> A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.

### For statement

*A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.*

> When a for loop executes, the following occurs:

* The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
* The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)
* The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
* If present, the update expression incrementExpression is executed.
Control returns to Step 2.

In JavaScript, the for statement declares the variable i and initializes it to 0. It checks that i is less than the number of options in the < select > element, performs the succeeding if statement, and increments i by 1 after each pass through the loop.

### While statement

*A while statement executes its statements as long as a specified condition evaluates to true.*

* If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop. The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while. To execute multiple statements, use a block statement ({ }) to group those statements.

Click to return [Home!](../README.md)
