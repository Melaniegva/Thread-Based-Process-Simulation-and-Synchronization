# Thread-Based-Process-Simulation-and-Synchronization
Java-based Operating Systems project simulating process execution and classic synchronization problems.
## Overview 
This academic project simulates process execution using Java threads and implements synchronization problems that can be encountered in operating systems. This project will focus on understanding how operating systems handle synchronization, process scheduling, and thread management. 

## Synchronization Problems Implemented:
-**Dining Philosophers**: Five Philosophers think and eat, sharing two forks (locks) to avoid deadlock.
-**Readers-Writers**: Multiple readers can access a shared resource simultaneously, but writers need exclusive access to the resource. 
-**Producer-Consumer**: A producer generates data and adds it to a buffer, while consumers consume the data, synchronized using semaphores and mutexes. 

## Features
-**Simulates Processes with Threads**: Each process is modeled as a thread. 
-**Synchronization**: Solves a classic synchronization problem using synchronization primitives like `Mutex`, `Semaphore`, and thread management.
-**Efficient Process Management**: Manages multiple threads for processes execution, showing resource contention and synchronization mechanisms. 
-**Activity Logging**: Tracks thread activity by logging the status, including start, wait for locks, acquire, and finish. 
