# Loops and Iterations-
Loops offer a quick and easy way to do something repeatedly.
There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

The statements for loops provided in JavaScript are:

* For statement-
A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
A for statement looks as follows:
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  
  * Do...while statement-
The do...while statement repeats until a specified condition evaluates to false.
A do...while statement looks as follows:
do
  statement
while (condition);
Copy to Clipboard
statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)

* While statement-
A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:
while (condition)
  statement
Copy to Clipboard
If the *condition *becomes false, statement within the loop stops executing and control passes to the statement following the loop.

* Labeled statement-
A label provides a statement with an identifier that lets you refer to it elsewhere in your program. For example, you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.

* Break statement-
Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.
When you use break without a label, it terminates the innermost enclosing while, do-while, for, or switch immediately and transfers control to the following statement.
When you use break with a label, it terminates the specified labeled statement.

* Continue statement-
The continue statement can be used to restart a while, do-while, for, or label statement.

When you use continue without a label, it terminates the current iteration of the innermost enclosing while, do-while, or for statement and continues execution of the loop with the next iteration. In contrast to the break statement, continue does not terminate the execution of the loop entirely. In a while loop, it jumps back to the condition. In a for loop, it jumps to the increment-expression. 

* For...in statement-
The for...in statement iterates a specified variable over all the enumerable properties of an object. For each distinct property, JavaScript executes the specified statements. A for...in statement looks as follows:

for (variable in object)
  statement
  
 * For...of statement
The for...of statement creates a loop Iterating over iterable objects (including Array, Map, Set, arguments object and so on), invoking a custom iteration hook with statements to be executed for the value of each distinct property.
