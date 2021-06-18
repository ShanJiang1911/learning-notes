## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)
* What is a ‘call’?
  * function invocation
* How many ‘calls’ can happen at once?
  * one at a time
* What does LIFO mean?
  * last in, first out.
* Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
  * 
    ```
    function firstFunction(){
    console.log("Hello from firstFunction");}

    function secondFunction(){
    firstFunction();
    console.log("The end from secondFunction");
    }
    secondFunction();
    ```
* What causes a Stack Overflow?
  * when there is a recursive function(a function that calls itself) without an exit point
## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
* What is a ‘refrence error’?
  * When you try to use a variable that is not yet declared
* What is a ‘syntax error’?
  * When user have something that cannot be parsed in terms of syntax
* What is a ‘range error’?
  * Try to manipulate an object with some kind of length and give it an invalid length
* What is a ‘tyep error’?
  * When the types (number, string and so on) user are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
* What is a breakpoint?
  * make the program stop at that point only if a condition is met
* What does the word ‘debugger’ do in your code?
  *  put in the line you want to break
Additional Resources
[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)


## Things I want to know more about
* how to do auto correction
[<--Back](README.md)