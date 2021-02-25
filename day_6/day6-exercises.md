**Chapter 3 Review Questions**

1.  If we have a function defined as `function sayHello(){console.log("Hello!")}`, what is the difference between entering `sayHello` and `sayHello()` in the console?
- sayHello() calls the funtion and the output will be 'Hello!'. Without the parentheses, the console will return [function: sayHello
]
2.  What is the difference between function parameters and arguments?
- Function paramenters act like variables. The value of the parameters could change each time the function is called. Function arguments have values assigned to the parameters.

3.  What is the keyword `return` used for?
- The return keyword is used to return a value to the code that called the function.

4.  How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?
- local variables removes the functions as soon as the function has finished its task. This means that if the function runs twice, the variable can have different values each time. Also two different functions can use variables with the same name without any kind of naming conflict. Global variables also use more memory than local variables. Scripts that require a lot of memory can perform slower, which in turn makes your web page take longer to respond to the user. 
