# Practice Quiz: Managing Computer Resources
**Total points:** 5 
**Score:** 100%

## Question 1
What is a memory profiler used for?

- It is used to store information. 
- It profiles an entire Python application.
- **It monitors memory consumption of a process over time, as well as the variables that require the most memory.**
- It modifies code.

*Memory profiler is a module that provides useful information about memory.*

## Question 2
Your application is having difficulty sending and receiving large packets of data, which are also delaying other processes when connected to remote computers. Which of the following will be most effective on improving network traffic for the application?

- Running the iftop program.
- Increase storage capacity.
- Increase memory capacity.
- **Use traffic shaping.**

*Traffic shaping can mark data packets and assign higher priorities when being sent over the network.*

## Question 3
What is the term referring to the amount of time it takes for a request to reach its destination, usually measured in milliseconds (ms)?

- Bandwidth
- **Latency**
- Number of connections
- Traffic shaping

*Latency is a measure of the time it takes for a request to reach its destination.*

## Question 4
If your computer is slowing down, what Linux program might we use to determine if we have a memory leak and what process might be causing it?

- **top**
- gparted
- iftop
- cron

*The top command will show us all running processes and their memory usage in Linux.*

## Question 5
Some programs open a temporary file, and immediately _____ the file before the process finishes, then the file continues to grow, which can cause slowdown.

- open
- close
- **delete**
- write to

*Sometimes a file is marked as deleted right after it is opened, so the program doesn't "forget" later. The file is then written to, but we can't see this as the file is already marked as deleted, but will not actually be deleted until the process is finished.*