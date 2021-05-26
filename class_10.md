# Error Handling and Debugging

If a Java statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

if you come across a an error while writing a script (or when someone reports a bug), you will neede to debug the code, track down the source of the error, and fix it. developers tools will help you with this task.

debugging is about deduction: eliminating potential cause of an error, there is a workflow for techniques that will help you narrow down the problem. first you should try to  narrow down the area where the problem may be.

### Where is the problem?

Look at the error message tell you.
- the relevant script that caused the problem

- the line number that became a problem for the interpreter

- the type of error (although thr underlying cause of the error may be different).

### What exactly is the problem?

when you have set breakpoints, you can see if the variablesaround them have the values you would expect them too. if not, look earlier in the script.
break down / break out parts of the code to test smaller pieces of the functionality.

- write values of variables into the console.

- call functions from the console to check if they are returning what you would expect them to.

- check if objects exist and have the methods / properties that you think they do.

The Javascript console will tell you when there is a problem with the script, where to look for the problem, and what kind of issue it seems to be.

If you understand execution contexts(which have two stages) and stacks, you are more likely to find the error in your code. Debugging is the processs of finding errors.  it involves a process of deduction. The console helps narrow down the area in which the error is located. JavaScript has 7 different types of errors. Each creates it's own error object, which can tell you it's line number and gives the discription of the error. If you know that you may get an error, you can handle it gracefully using try, catch, finally statements. Use them to give you users helpful feedback.


