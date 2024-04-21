# Practice Quiz: Code that crashes
**Total points:** 5 
**Score:** 100%

## Question 1
Which of the following will let code run until a certain line of code is executed?

- **Breakpoints**
- Watchpoints
- Backtrace
- Pointers

*Breakpoints let code run until a certain line of code is executed.*

## Question 2
Which of the following is NOT likely to cause a segmentation fault?

- Wild pointers
- Reading past the end of an array
- Stack overflow
- **RAM replacement**

*Segmentation fault is not commonly caused by a new RAM card in the system.*

## Question 3
A common error worth keeping in mind happens often when iterating through arrays or other collections, and is often fixed by changing the less than or equal sign in our for loop to be a strictly less than sign. What is this common error known as?

- Segmentation fault
- backtrace
- The No such file or directory error
- **Off-by-one error**

*The Off-by-one bug, often abbreviated as OB1, frequently happens in computer programming when an iterative process iterates one time too many or too little.*

## Question 4
A very common method of debugging is to add print statements to our code that display information, such as contents of variables, custom error statements, or return values of functions. What is this type of debugging called?

- Backtracking
- Log review
- **Printf debugging**
- Assertion debugging

*Printf debugging originated in name with using the printf() command in C++ to display debug information, and the name stuck. This type of debugging is useful in all languages.*

## Question 5
When a process crashes, the operating system may generate a file containing information about the state of the process in memory to help the developer debug the program later. What are these files called?

- Log files
- **Core files**
- Metadata file
- Cache file

*Core files (or core dump files) record an image and status of a running process, and can be used to determine the cause of a crash.*

## Question 6
You are a software developer who has been asked to write a program for a banking company. Your manager suggests you use assert statements in your code. What is the purpose of using assert statements in code?

- To determine the code’s runtime.
- To translate the code to a different language.
- **To catch issues and debug your code during development.**
- To rewrite code that produces errors.

*An assert statement is beneficial to developers as it helps determine if bugs are in your code and where they are located.*

## Question 7
How does the print statement help programmers debug codes?

- **It produces the output of the code.**
- It fixes the errors of the code.
- It prints the details of the code.
- It recommends the correct code.

*The print statement sends messages or prints out the values to the output screen. If the code has errors, the command will produce the error statement as output.*

## Question 8
Visual Studio Code or VS Code, popular among programmers, utilizes breakpoints. What is a breakpoint?

- An open-source product from Microsoft.
- **A debugging technique.** 
- An integrated developer environment (IDE).
- A location where the code error occurs .

*A breakpoint is not a location where you find code errors. It is a debugging technique where you set a stopping point on a specific line of code.*

## Question 9
Imagine that you’re working on a new feature for a web application. As you're writing the code, you realize that certain sections might produce runtime errors. Which Python mechanism allows you to handle runtime errors without crashing the program? 

- Print debugging
- Assert statements
- **Try and except blocks**
- If-else conditions

*The try and except blocks in Python are specifically designed to catch and handle exceptions (runtime errors). Code that might produce an error is placed inside a try block. If an error occurs, instead of crashing the program, the code inside the except block is executed.*

## Question 10
You’re a web developer for an e-commerce website, and you're noticing an increase in unexpected behaviors and errors as the site’s user base grows. Why might you choose to implement the Python logging module in your e-commerce website over traditional print() statements?

- The logging module can only display messages on the console, similar to the print() function.
- **The logging module allows categorization of log messages based on their severity, such as DEBUG, INFO, WARNING, ERROR, and CRITICAL.**
- The logging module can only capture error messages.
- The logging module requires a third-party library to be installed.

*One of the key features of the logging module is its ability to categorize log messages based on severity levels. This helps in filtering and prioritizing issues, making it easier to diagnose and address problems.*

## Question 11
Which of the following are key features of the pdb debugger in Python? Select all that apply.

- **Setting breakpoints to pause program execution at specific lines.**
- **Stepping through code to observe the execution flow in detail.**
- Automatically optimizing code for better performance.
- **Inspecting and changing current values of variables during a debugging session.**

*One of the primary features of pdb is the ability to set breakpoints in the code.*

*pdb allows developers to step through code, observing the execution flow line by line.*

*With pdb, developers can inspect—and alter—the values of variables at any point during a debugging session.*