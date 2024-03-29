# What is Debugging

![](https://miro.medium.com/max/875/1*hEKtQJJwV1bvlP5NgX8fyg.png)

> Debugging is a process for testing, finding the errors and reducing them from happening in future.
> Debugging JavaScript either requires having support for JavaScript debugger
> keyword, breakpoint support with web browser tools, or third-party tools.
> These tools range from browser plugins like Augury which is an Angular development and debugging 
> extension for Chrome, third-party tools & more. It is also possible to use ‘debugger’ keyword support
> (depending on the browser type and version) and to freeze the code at a >given point and investigate the issue. 
> Let us look at few popular debugging and error handling tools.



# Why errors happened ?
> ***some times the excution order can be the reason to have an error, because some asks cannot complete until another statement or function has been run in a certain order.***

# Error Handling & Debugging..
> ***JavaScript can be hard to learn and everyone makes mistakes when writing it.***
> ***Error Handling & Debugging will help you learn how to find the errors in your code.***
> ***It will also teach you how to write scripts that deal with potential errors gracefully.***

> *When you are writing JavaScript, do not expect to write it perfectly the first time. Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the computer to solve it. too.*

*When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it.*

<hr>

# ORDER OF EXECUTION

***To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.***



![](https://github.com/batoolalomari/201readingNote/raw/master/or.png)




* The greeting variable gets its value from the greetUser() function.
* greetUser() creates the message by combining the string 'He 11 o ' with the result of getName ().
* getName () returns the name to greetUser() .
* greetUser() now knows the name, and combines it with the string. It then returns the message to the statement that ca lled it in step 1.
* The value of the greeting is stored in memory.
* This greeting variable is written to an alert box.


***There are 3 types of errors in programming:***

- Syntax Errors : Occur at compile time in traditional programming languages and at interpretation time in JavaScript.
- Run time Error : Also called exceptions, occur during execution (after compilation/interpretation).
- Logical Error : Logic errors can be the most difficult type of errors to track down.


Exception Handling:
Exception handling is accomplished with a try…catch statement. When the program encounters an exception, the program will terminate in an unfriendly fashion. To safeguard against this unanticipated error, we can wrap our code in a try…catch statement.

<hr>


- There are seven types of built-in error objects in JavaScript.
***SyntaxError***
*SYNTAX IS NOT CORRECT :* This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.
***ReferenceError***
*VARIABLE DOES NOT EXIST :* This is caused by a variable that is not declared or is out of scope.
***EvalError***
*INCORRECT USE OF eval() FUNCTION The eval () * function evaluates text through the interpreter and runs it as code. It is rare that you would see this type of error, as browsers often throw other errors when they are supposed to throw an Eva 1 Error.
***URIError***
*INCORRECT USE OF URI FUNCTIONS :* If these characters are not escaped in URls, they will cause an error: / ? & I : ;
***TypeError***
*VALUE IS UNEXPECTED DATA TYPE :* This is often caused by trying to use an object or method that does not exist.
***RangeError***
*NUMBER OUTSIDE OF RANGE :* If you call a function using numbers outside of its accepted range.
***Error***
*GENERIC ERROR OBJECT :* The generic Error object is the template (or prototype) from which all other error objects are created.

<hr>

# The Stack
> *The JavaScript interpreter processes one line of code at a time. when a statement needs data from another function it stacks the new function on top of the current task.*


![](https://github.com/batoolalomari/201readingNote/raw/master/st.png)


# EXECUTION CONTEXT & HOISTING
> *Each time a script enters a new execution context, there are two phases of activity:*

![](https://github.com/batoolalomari/201readingNote/raw/master/ho.png)


# HANDLING EXCEPTIONS
*If you know your code might fail, use try, catch, and finally. Each one is given its own code block.*


           ``` ruby
           try {
               // Try to execute this code
               
           }catch (exception) {
               // If there is an exception, run this code
               
           }fina ll y {
              // This always gets executed
           }
           ```



