EXECUTION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts

There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 


EXECUTION CONTEXT
JavaScript
Hello Molly
Every statement in a script lives in one of three
execution contexts:
Q GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
Q EVAL CONTEXT (NOT SHOWN)
Text is executed like code in an internal function
called eva l {) (which is not covered in this book).
VARIABLE SCOPE
The first two execution contexts correspond with the
notion of scope (which you met on p98):
Q GLOBAL SCOPE
If a variable is declared outside a function, it can
be used anywhere because it has global scope.
If you do not use the var keyword when creating
a variable, it is placed in global scope.
FUNCTION-LEVEL SCOPE
When a variable is declared within a function,
it can only be used within that function. This is
because it has function-level scope.
EXECUTION CONTEXT
& HOISTING
Each time a script enters a new execution context, there are two phases
of activity: 
1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined  
 2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements   
 UNDERSTANDING
SCOPE 
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object. 

Functions in JavaScript are said to have lexical scope.
They are linked to the object they were defined within.
So, for each execution context, the scope is the
current execution context's variables object, plus the
variables object for each parent execution context. Imagine that each function is a nesting doll.
The children can ask the parents for information in
their variables. But the parents cannot get variables
from their children. Each child will get the same
answer from the same parent. 



UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handl ing code. 
