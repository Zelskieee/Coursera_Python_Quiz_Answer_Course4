# Practice Quiz: Understanding slowness
**Total points:** 5  
**Score:** 100%

## Question 1
Which of the following will an application spend the longest time retrieving data from?

- CPU L2 cache
- RAM
- Disk
- **The network**

*An application will take the longest time trying to retrieve data from the network.*

## Question 2
Which tool can you use to verify reports of 'slowness' for web pages served by a web server you manage?

- The top tool
- **The ab tool**
- The nice tool
- The pidof tool

*The ab tool is an Apache Benchmark tool used to figure out how slow a web server is based on average timing of requests.*

## Question 3
If our computer running Microsoft Windows is running slow, what performance monitoring tools can we use to analyze our system resource usage to identify the bottleneck? (Check all that apply)

- **Performance Monitor**
- **Resource Monitor**
- Activity Monitor
- top

*Performance Monitor is a system monitoring program that provides basic CPU and memory resource measurements in Windows.*

*Resource Monitor is an advanced resource monitoring utility that provides data on hardware and software resources in real time.*

## Question 4
Which of the following programs is likely to run faster and more efficiently, with the least slowdown?

- A program with a cache stored on a hard drive.
- **A program small enough to fit in RAM.**
- A program that reads files from an optical disc.
- A program that retrieves most of its data from the Internet.

*Since RAM access is faster than accessing a disk or network, a program that can fit in RAM will run faster.*

## Question 5
What might cause a single application to slow down an entire system? (Check all that apply)

- **A memory leak.**
- **The application relies on a slow network connection.**
- Handling files that have grown too large.
- Hardware faults.

*Memory leaks happen when an application doesn't release memory when it is supposed to.*

*If files generated by the application have grown overly large, slowdown will occur if the application needs to store a copy of the file in RAM in order to use it.*