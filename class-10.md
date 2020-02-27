### EXECUTION CONTEXT:
* GLOBAL CONTEXT
* FUNCTION CONTEXT
* EVAL CONTEXT (NOT SHOWN)

### VARIABLE SCOPE:
* VARIABLE SCOPE
* FUNCTION-LEVEL SCOPE

### Each time a script enters a new execution context, there are two phases of activity:
* PREPARE:
  * The new scope is created
  * Variables, functions, and arguments are created
  * The value of the this keyword is determined
* EXECUTE:
  * Now it can assign values to variables
  * Reference functions and run their code
  * Execute statements

  ### Error Type :
  * Syntax Error
  * Ref erenceError
  * EvalError
  * URI Error
  * Type Error
  * RangeError
  * Error :GENERIC ERROR OBJECT
  * NaN :NOT AN ERROR


  ### HOW TO DEAL WITH ERRORS:
  * DEBUG THE SCRIPT TO FIX ERRORS
  * HANDLE ERRORS GRACEFULLY 

  ### A DEBUGGING WORKFLOW:
  #### WHERE IS THE PROBLEM?
  1. Look at the error message, it tells you:
     * The relevant script that caused the problem.
     * The line number where it became a problem for the interpreter. 
     * The type of error (although the underlying cause of the error may be different).
  2. Check how far the script is running: Use tools to write messages to the console to tell how far your script has executed.
  3. Use breakpoints where things are going wrong. They let you pause execution and inspect the va lues that are stored in variables.

  #### WHAT EXACTLY IS THE PROBLEM?
  1. When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.
  2. Break down I break out parts of the code to test smaller pieces of the functionality.
    *  Write values of variables into the console.
    *  Calrfunctions from the console to check if they are returning what you would expect them to.
    *  Check if objects exist and have the methods I properties that you think they do.
  3. Check the number of parameters for a function, or the number of items in an array. 

  ### You can pause the execution of a script on any line using breakpoints. Then you can check the va lues stored in variables at that point in time. 
 
  #### HANDLING EXCEPTIONS :
  * TRY :First, you specify the code that you t hink might throw an exception within the try block.
  * CATCH :If the try code block throws an exception, catch steps in with an alternative set of code.
  * FINALLY :The contents of the fina11y code block will run either way - whether the try block succeeded or failed.

  ### Debugging is the process of finding errors. It involves a process of deduction.
  ### The console helps narrow down the area in which the error is located, so you can try to find the exact error.
