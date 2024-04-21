# Practice Quiz: Performance tuning in Python scripts
**Total points:** 10 
**Score:** 100%

## Question 1
Which of the following best describes a CPU-bound task?

-A task that frequently waits for network responses.
- A task that consistently requires more memory than is available.
- A task that often waits for I/O operations to complete.
- **A task that primarily utilizes only one of the available CPU cores, even when others are free.**

## Question 2
How does rsync (remote sync) primarily optimize data transfer?

- rsync prioritizes files based on their importance and transfers critical files first.
- rsync uses advanced compression algorithms to reduce the size of files before transferring.
- rsync duplicates all files every time to ensure no data is missed during transfer.
- **rsync transfers and synchronizes files by comparing the modification time and size, ensuring only changed data is transferred.**

## Question 3
In the Qwiklab, what did you use the psutil.disk_io_counters() function to do?


- To configure network interface parameters.
- To monitor real-time network traffic.
- **To retrieve disk I/O statistics.**
- To estimate file space usage on the disk.

## Question 4
In the lab, you employed multiprocessing to reduce backup time. Why was multiprocessing the right choice in this example?

- **The task was CPU-bound, and multiprocessing leveraged unused CPU cores to run the script significantly faster.**
- It added timestamps to each operation, which enabled better tracking.
- It reduced the number of variables used to speed up the process.
- It leveraged a faster internet connection to fix the network bottleneck.

## Question 5
True or false: psutil is a cross-platform library for retrieving information on running processes and system utilization (CPU, memory, disks, network, sensors) in Python. 

- **True**
- False

## Question 6
True or false: In order to check how much your program utilizes CPU using psutil.cpu_percent(), you first need to install the pip3 which is a Python package installer. 

- **True**
- False

## Question 7
IIn the multisync.py script, what is the role of the map method of the Pool object?

- **To distribute the tasks evenly across available CPUs.**
- To map the output of one task to the input of another.
- To map all tasks to a single processor.
- To create a mapping of task dependencies.

## Question 8
Which of the following are options for the rsync command? Select all that apply.

- -p
- **-a**
- **-v**
- **-z**

## Question 9
What is the correct order of arguments when using the rsync command?

- [Destination] [Options] [Source-Files-Dir]
- [Source-Files-Dir] [Destination] [Options]
- [Options] [Destination] [Source-Files-Dir]
- **[Options] [Source-Files-Dir] [Destination]**

## Question 10
The multiprocessing module in Python is used to prevent bottlenecks in which of the following? 

- **CPU-bound tasks.**
- I/O-bound tasks.
- Network-bound tasks.
- Memory-bound tasks.