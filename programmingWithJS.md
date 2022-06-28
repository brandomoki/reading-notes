
## **Programming with Java Script**

### Control Flow

+ The control flow is the order in which the computer executes statements in a script.

+ Code is run in order from the first line in the file to the last line, unless the pc runs across the (frequent) structures that change the control flow, such as conditionals and loops

+ Example below
`if (field==empty) {`
    `promptUser();`
`} else {`
    `submitForm();`
`}`

+ Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

### JS Functions

+ A JS function is a block of code thatis designed to perform a task

+ **JS Function Syntax**
`function name(parameter1, parameter2, parameter3) {`
  `// code to be executed`
`}`

+ Function parameters are listed inside the parentheses ()
+ Function arguments are the values received by the function when it is invoked.
+ Inside the function the arguments (the parameters) behave as local variables

+ **Function Invocation**

+ The code inside the function will execute when "something" invokes (calls) the function
    + When an event occurs (when user clicks a button)
    + When it is invoked (called) from JS
    + Automatically (self invoked)

+ **Function Return**
    + When JS reaches a `return` statement, the function will stop executing

+ **Why Functions?**
    + You can reuse code: Define it once and use it many times.
    + You can use the same code many timeswith different arguments to produce different results

### JavaScript Operators

 >  Operator Description  

>`+`	Addition

>`-`	Subtraction

>`*`	Multiplication

>`**`	Exponentiation (ES2016)

>`/`	Division

>`%`	Modulus (Division Remainder)

>`++`	Increment

>`--`	Decrement

### JavaScript Assignment Operators

> 
Operator,	Example,	Same As
>    =,x = y,	x = y
 
  >   +=,	x += y,	x = x + y
  
  >  -=,	x -= y,	x = x - y
   
  >  *=,	x *= y,	x = x * y
   
  >  /=,	x /= y,	x = x / y
   
  >  %=,	x %= y,	x = x % y
   
  >  **=,	x **= y,	x = x ** y