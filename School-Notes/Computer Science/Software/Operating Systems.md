An OS serves as a middle-man for communication between the computer's hardware and software. Software applications cannot talk directly to the hardware OS examples include:
- Windows
- Linux
- IOS
- Android (Linux)
An OS has to handle resource management (Processor scheduling, memory management, backing store management and IO management), and provision of a user interface (Command line, Menu driven or GUI).

# Memory Management
A PC allows many processes to be running at the same time. You could be listening to music, writing a program, checking your emails, printing a document and have a web browser running in the background. The OS allocates memory to each process. If there is not enough memory, a program may be swapped onto the disk or "virtual memory".

# Processor Scheduling
The OS Controls which programs can send data to the processor. Instructions from multiple operations are queued, the processor executes small parts of each operation in turn so that programs appear to run simultaneously. This is known as multi-tasking

# The Scheduler
The scheduler is the operating system module responsible for ensuring that processor time is used as efficiently as possible. There are different scheduling algorithms:
- Round Robin: Each process in turn has use of the processor for a given time slice
- Shortest Job Next
- Priority System

# Backing Store Management
The keeps track of where all files are stored on hard disk or external drives, and where space is free to be used. Files can be listed, moved, deleted, protected from unauthorised access.

# IO Device Management
It communicates with IO devices via the IO controller, part of the CPU, checks that a required output device is switched on and ready to receive data. It can also deal with processor 'interrupts' such as "Out of paper' message from a printer.