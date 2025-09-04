# C Projects Portfolio

This portfolio showcases projects developed in **C**, focusing on command-line tools, algorithms, and problem-solving.  

---

# UNIX Command Interpreter (C)

A custom terminal written in **C** that replicates basic UNIX shell functionality, supporting multitasking, memory management, and script execution.

## Features

- **Shell Commands**: `cd`, `ls`, `mkdir`, `touch`, `echo`, `set`, `print`, `source`, `run`  
- **Script Execution**: Execute scripts (`source`) and background processes (`exec`)  
- **Multitasking & Scheduling**: Implements PCBs and ready queue with **FCFS**, **SJF**, **RR**, and **Aging** policies  
- **Memory Management**: Frame-based allocation, page tables, and page fault handling  
- **Variable Support**: Store and retrieve variables using `$VAR` syntax  
- **File & Directory Operations**: List files alphabetically, create directories/files, navigate directories with validation  
- **Error Handling**: Detects invalid commands, missing files, memory limits, and incorrect arguments  

👉 [Project Repository](https://github.com/PiaCarlos/Implementation-of-a-Terminal-/tree/main) 

---

# Thread-Safe Queue (C)

A synchronized **doubly-linked queue** in C for multi-threaded producer-consumer scenarios.  

## Features

- **Thread-Safe**: Enqueue and dequeue operations protected by `pthread` mutexes  
- **Multi-Threaded**: Supports multiple producers and consumers  
- **Dynamic Memory**: Nodes allocated and freed safely  
- **Blocking Dequeue**: Ready for semaphore-based blocking extensions  
- **Resource Management**: Clean destruction of all nodes and locks  

👉 [Project Repository](https://github.com/PiaCarlos/Thread-Safe-Queue) 


---

## MiniCalc – Command-Line Calculator
A lightweight calculator implemented in C that supports basic arithmetic, number theory, and string operations.  

- Operations: addition, GCD of multiple numbers, square root, and anagram detection.  
- Strong input validation and descriptive error handling with exit codes.  
- Demonstrates argument parsing, numeric conversions, and string processing.  

👉 [Project Repository](https://github.com/PiaCarlos/MiniCalc) 

---

## Mini Database (C)

A lightweight database in C with dynamic storage and CSV file support.  

### Features
- Resizable array for records (auto capacity doubling).  
- Append, index access (with bounds checking), and lookup by handle.  
- Load and save records in CSV format.  
- Proper memory management with `malloc`, `realloc`, and `free`.  

👉 [Project Repository](https://github.com/PiaCarlos/mini-database)
