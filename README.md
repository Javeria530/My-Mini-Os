# Mini Operating System

Mini Operating System is an academic Computer Science project developed to explore fundamental operating-system concepts, particularly process management, CPU scheduling, and memory management.

## Project Overview

Operating systems manage hardware resources and coordinate the execution of multiple programs.

This project applies core operating-system concepts through practical implementation and simulation.

## Core Concepts

- Process Management
- CPU Scheduling
- Memory Management
- Process States
- Resource Management
- Operating-System Algorithms

## Process Management

A process represents a program currently being executed.

A simplified process lifecycle is:

```text
New
 |
 v
Ready
 |
 v
Running
 |
 +------> Waiting / Blocked
 |               |
 |               v
 |             Ready
 |
 v
Terminated
```

## CPU Scheduling

CPU scheduling determines which process receives CPU execution time.

Important scheduling concepts include:

- Arrival Time
- Burst Time
- Completion Time
- Waiting Time
- Turnaround Time
- Process Priority
- Context Switching

## Scheduling Metrics

Turnaround Time:

```text
Turnaround Time = Completion Time - Arrival Time
```

Waiting Time:

```text
Waiting Time = Turnaround Time - Burst Time
```

## Memory Management

Memory management is responsible for allocating and managing memory used by processes.

Important concepts include:

- Physical Memory
- Virtual Memory
- Pages
- Frames
- Paging
- Page Tables
- Page Faults
- Memory Allocation
- Fragmentation

## Context Switching

A context switch occurs when CPU execution changes from one process to another.

The operating system saves the state of the current process and restores the state of the next process.

## Installation

Clone the repository:

```bash
git clone https://github.com/Javeria530/My-Mini-Os.git
cd My-Mini-Os
```

Open the project source files using the compiler or development environment required by the implementation.

## Concepts Demonstrated

- Operating Systems
- Process Management
- CPU Scheduling
- Memory Management
- Process States
- Context Switching
- Resource Management
- Data Structures
- Algorithms
- Low-Level System Concepts

## Future Improvements

- Additional CPU scheduling algorithms
- Scheduling visualization
- Process Control Block simulation
- Deadlock detection
- Page replacement algorithms
- Virtual-memory simulation
- Performance comparison
- Automated testing

## Author

Javeria Iqbal

Computer Science Graduate  
National University of Computer and Emerging Sciences (NUCES)

GitHub: https://github.com/Javeria530
