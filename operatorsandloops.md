### Operators and Loops

+ JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator

`operand1 operator operand2`

+ Unary operator requires a single operand, either before or after the operator

`operator operand`
or
`operand operator`

### **Assignment Operators**

>+ An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.


> Name______________________Shorthand operator____________________Meaning

> Assignment_______________________x = f()__________________________x = f()

> Addition assignment_____________x += f()	________________________x = x + f()

> Subtraction assignment___________x -= f()	________________________x = x - f()

> Multiplication assignment________x *= f()	________________________x = x * f()

> Division assignment______________x /= f()	________________________x = x / f()

> Remainder assignment_____________x %= f()	________________________x = x % f()

> Exponentiation assignment________x **= f()	____________________x = x ** f()

> Left shift assignment____________x <<= f()	____________________x = x << f()

> Right shift assignment___________x >>= f()	____________________x = x >> f()

> Unsigned right shift assignment__x >>>= f()	____________________x = x >>> f()

> Bitwise AND assignment___________x &= f()	________________________x = x & f()

> Bitwise XOR assignment___________x ^= f()	________________________x = x ^ f()

> Bitwise OR assignment____________x |= f()	________________________x = x | f()

> Logical AND assignment___________x &&= f()	____________________x && (x = f())

> Logical OR assignment____________x ||= f()	____________________x || (x = f())

> Logical nullish assignment_______x ??= f()	____________________x ?? (x = f())


### Comparison Operators

+ A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the `===` and `!==` operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality

### Loops

+ A **for** loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

+ The **do...while** statement repeats until a specified condition evaluates to false.

+ A **while** statement executes its statements as long as a specified condition evaluates to true.

`forLoopExample();`
`function forLoopExample(){`
     1. variable declaration & assignment
     2. condition that needs to be met
     3. what do we do with the variable once an iteration has completed

 `doWhileExample();`
`function doWhileExample(){`