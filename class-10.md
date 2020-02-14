# Error Handling and Debugging
* Order of execution
  * The order in which statements are processed
* Hoisting 
  * Moving declarations to the top
* Variables object
  * contains details of all of the variables, functions, and parameters for that execution context
* Lexical scope
  * functions are linked to the object they were defined within
* Summary
  * If you understand execution contexts and stacks, you are more likely to find the error in your code
  * Debugging is the process of finding errors. it involves a process of deduction
  * The console helps narrow down the area in which the error is located, so you can try to find the exact error
  * JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error
  * If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.