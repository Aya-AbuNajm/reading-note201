# JS Debugging
The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.
## EXECUTION CONTEXT
Every statement in a script lives in one of three execution contexts:

* GLOBAL CONTEXT Code that is in the script, but not in a function. There is only one global context in any page.
* FUNCTION CONTEXT Code that is being run within a function.Each function has its own function context.
* EVAL CONTEXT (NOT SHOWN) Text is executed like code in an internal function called eval() .
![scop](https://miro.medium.com/max/582/1*xOEvF63MASlMji9-CjZqbQ.jpeg)
## VARIABLE SCOPE
The first two execution contexts correspond with the notion of scope :

1.**GLOBAL SCOPE** If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope.
2. **FUNCTION-LEVEL** SCOPE When a variable is declared within a function,it can only be used within that function. This is because it has function-level scope.

## EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:

### PREPARE
- The new scope is created
- Variables, functions, and arguments are created
- The value of the this keyword is determined
### EXECUTE
- Now it can assign values to variables
- Reference functions and run their code
- Execute statements


## ERROR OBJECTS
< Error objects can help you find where your mistakes are and browsers have tools to help you read them.

### error object contanin:
- name         :	Type of execution
- message      :     Description
- fileNumber   :     Name of the JavaScript file
- lineNumber   :	Line number of error

### Seven types of built-in error objects in JavaScript:

1. Error	        Generic error - the other errors are all based upon this error
2. Syntax Error	    Syntax has not been followed
3. ReferenceError	Tried to reference a variable that is not declared/within scope
4. TypeError	    An unexpected data type that cannot be coerced
5. Range Error   	Numbers not in acceptable range
6. URI Error	    encodeURI ().decodeURI(),and similar methods used incorrectly
7. EvalError	    eval () function used incorrectly

### CONSOLE METHODS
* console.info() can be used for general information
* console.warn() can be used for warnings
* console.error() can be used to hold errors
* console.log
![imgconsol](https://tutorialstonight.com/assets/js/javascript-console-methods.png)
### WRITING TABULAR DATA :

**console.table() method** lets you output a table showing(objects, arrays that contain other objects or arrays)
WRITING ON A CONDITION:

**console.assert() method** you can test if a condition is met, and write to the console only if the expression evaluates to false.

## HANDLING EXCEPTIONS
* **TRY** First, you specify the code that you t hink might throw an exception within the try block.If an exception occurs in this section of code, control is automatically passed to the corresponding catch block. The try clause must be used in this type of error handling code, and it should always have either a catch, finally, or both.If you use a continue, break, or return keyword inside a try, it will go to the finally option.
* **CATCH** If the try code block throws an exception, catch steps in with an alternative set of code. It has one parameter: the error object. Although it is optional, you are not handling the error if you do not catch an error. The ability to catch an error can be very helpful if there is an issue on a live website. It lets you tell users that something has gone wrong (rather than not informing them why the site stopped working).
* **FINALLY** The contents of the finally code block will run either way - whether the try block succeeded or failed. It even runs if a return keyword is used in the try or catch block. It is sometimes used to clean up after the previous two clauses. These methods are similar to the .done(), .fail() , and .a1ways() methods in jQuery. You can nest checks inside each other (place another try inside a catch), but be aware that it can affect performance of a script.

## DEBUGGING TIPS
![debug](https://media.geeksforgeeks.org/wp-content/uploads/20190902105053/Debugging-Tips-To-Get-Better-At-It.png)
* ANOTHER BROWSER
* ADD NUMBERS
* STRIP IT BACK
* SEARCH
* CODE PLAYGROUNDS
* VALIDATION TOOLS