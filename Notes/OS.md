# Operating System (OS) Notes

## 1. Introduction
- Operating System = Software that manages hardware & software resources.
- Acts as an interface between user & hardware.
- Functions: process management, memory management, file system, I/O handling, security.

## 2. Types of Operating Systems
- **Batch OS** → Executes jobs in batches, no user interaction.
- **Multiprogramming OS** → Runs multiple programs at once by sharing CPU.
- **Multitasking OS** → Allows users to perform many tasks at the same time.
- **Time Sharing OS** → Multiple users share system resources simultaneously.
- **Distributed OS** → Runs on multiple machines, appears as single system.
- **Real-Time OS (RTOS)** → Used in critical systems (aircraft, medical), strict timing.

## 3. Process Management
- **Process**: Program in execution.
- **Process States**: New → Ready → Running → Waiting → Terminated.
- **Process Control Block (PCB)**: Stores info about process (PID, state, registers, memory).
- **CPU Scheduling**:
  - FCFS (First Come First Serve)
  - SJF (Shortest Job First)
  - Priority Scheduling
  - Round Robin (time quantum based)
  - Multilevel Queue

## 4. Threads
- **Thread** = lightweight process.
- Types: User-level threads, Kernel-level threads.
- Multithreading improves CPU utilization.

## 5. Deadlocks
- Deadlock = processes wait forever due to resource holding.
- Conditions (Coffman): Mutual Exclusion, Hold & Wait, No Preemption, Circular Wait.
- Handling:
  - Prevention
  - Avoidance (Banker’s Algorithm)
  - Detection & Recovery

## 6. Memory Management
- **Swapping**: Process moved between RAM & disk.
- **Partitioning**:
  - Fixed Partition
  - Dynamic Partition
- **Paging**: Divide memory into fixed-size blocks.
- **Segmentation**: Divide memory into variable-size segments.
- **Virtual Memory**: Logical memory > physical memory, uses paging + swapping.

## 7. File System
- Functions: create, delete, read, write, manage storage.
- **File Allocation Methods**:
  - Contiguous Allocation
  - Linked Allocation
  - Indexed Allocation

## 8. I/O Management
- I/O devices managed by OS via device drivers.
- **Spooling**: Overlapping I/O & CPU by buffering (e.g., printing).

## 9. Security
- OS provides authentication, authorization, encryption, firewalls.
