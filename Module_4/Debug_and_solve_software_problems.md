# Practice Quiz: Debug and solve software problems
**Total points:** 10 
**Score:** 100%

## Question 1
Identify the elements involved in generating the report in the start_date_report.py script. Select all that apply.

- **Parsing date inputs from user.**
- **Generating output based on the start date.**
- Processing hourly data.
- **Handling TypeError for date inputs.**

## Question 2
What type of error caused the start_date_report.py script to crash?

- FileNotFoundError
- ValueError
- SyntaxError
- **TypeError**

## Question 3
What steps did you take to reproduce the TypeError message in the start_date_report.py script? Select all that apply.

- Modify the script code by altering function parameters to intentionally produce a similar error.
- Run the script and enter varying year, month, and day values to trigger the error.
- Use a debugging tool to trace the script's execution and monitor variable states at error occurrence.
- **Observe the script's behavior when provided with out-of-range or non-numeric input scenarios.**

## Question 4
In the context of the lab, which of the following is a key indicator that a script has been successfully optimized?

- Ability to process larger files only.
- **Reduced execution time to a few seconds for report generation.**
- Enhanced graphical user interface.
- Increased complexity for better accuracy.

## Question 5
Complete this sentence. To fix the error found in the lab, you need to cast the data type of the year, month, and day values to _____. 

- to concatenating strings
- **integers**
- text and use the print () function
- revise the call parameters

## Question 6
After you debugged the original error and fixed it, you discover that processing the file to print a report takes a long time. How do you fix this issue?

- **Modify the get_same_or_newer() function.**
- Run the Python script start_date_report.py earlier in the process. 
- Check the execution time: time ./test.py.
- Nothing. Speed is dependent on the size of the dataset.

## Question 7
How does preprocessing the file in the start_date_report.py script specifically address the problem of slow report generation?

- It compresses the file for quicker loading and processing times.
- It indexes the file for faster search operations within the script.
- It cleans and sanitizes the data for error-free processing.
- **It organizes data by start dates for efficient access, reducing the need for repetitive calculations.**

## Question 8
According to this QwikLab, what is an effective strategy for dealing with complex debugging issues like the ones encountered in the start_date_report.py script?

- Consult online forums and communities for similar issues and solutions.
- Implement automated testing to identify all issues at once.
- **Break down the problem into smaller, more manageable parts for targeted resolution.**
- Completely rewrite sections of the script to avoid dealing with complex issues.

## Question 9
After debugging and fixing the initial problem in the lab, you need to optimize file processing and printing speed. What steps should you take for preprocessing the file? Select all that apply.

- **Create a dictionary using start dates as keys to replace repetitive calculations.**
- **Sort the data by start_date, then process it date by date.**
- Sequentially process the data starting from the earliest start_date.
- **Compile a dictionary to organize start dates for sequential use in the script.**

## Question 10
You are optimizing a Python script similar to the one in the lab, designed to generate reports from a large dataset of employee start dates. The script currently processes the entire dataset each time a report for a specific date is requested, leading to slow performance. What change should you implement to improve the efficiency of the script?

- Implement multithreading to process different parts of the dataset in parallel.
- Increase the hardware resources allocated to the script, such as CPU and memory.
- **Modify the script to use the get_same_or_newer() function, which generates output that is reusable for multiple dates.**
- Rewrite the entire script using a more efficient programming language.