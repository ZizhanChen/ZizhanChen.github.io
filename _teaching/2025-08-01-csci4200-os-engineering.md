---
title: "CSCI4200: Operating System Engineering"
collection: teaching
type: "Undergraduate Course"
permalink: /teaching/2025-08-01-csci4200-os-engineering
venue: "The Chinese University of Hong Kong, Department of Computer Science and Engineering"
date: 2025-08-01
location: "Shatin, N.T., Hong Kong"
---

## Course Description

This course introduces fundamental design and implementation in the engineering of operating systems. Students will learn how to implement a small operating system with a step-by-step approach through hands-on experiences. Topics include booting, user/kernel mode, interrupt/exception, system calls, tasking, paging, interrupt handling, I/O and terminal, context switch, block device driver, file systems, virtual memory, and process implementation.

---

## General Information

**Lectures & Tutorials/Labs**
- **15:30 – 16:15, Tuesday** – Y.C. Liang Hall 101 (Tutorial/Lab)
- **16:30 – 17:15, Tuesday** – Y.C. Liang Hall 101 (Tutorial/Lab)
- **12:30 – 14:15, Wednesday** – William M W Mong Eng Bldg 401 (Lecture)

**Textbooks:**
- *Orange'S: The Implementation of an Operating System*, Yuan YU, Publishing House of Electronic Industry, China, 2009.
- *A Heavily Commented Linux Kernel Source Code*, Zhao Jiong.
- *Operating Systems Design and Implementation*, 3rd Edition. Andrew S. Tanenbaum and Albert S. Woodhull, Pearson Prentice Hall, 2006.

---

## Course Materials: Lectures, Tutorials, and Labs

### Lecture 0: Introduction to the Course
### Lecture 1: Experimental Environment
- [Tutorial 1 (Slides)]()
- OSLAB Software Package (simulator, compiler)

### Lecture 2: Real Mode of Intel 80386 and Booting
- [Lecture Slides (Intel 8086)]()
- [Tutorial 2 (Slides)]()
- booting program (assembly)

### Lecture 3: "Hello World" in Real Mode
- [Tutorial 3 (Slides)]()
- Hello World in real mode (assembly)

### Lecture 4: "Hello World" in Protected Mode
- [Lecture Slides (Intel 80386)]()
- [Tutorial 4 (Slides)]()
- Hello World in protected mode (assembly)

### Lecture 5: Interrupts/Exceptions in Protected Mode
- [Tutorial 5 (Slides)]()
- Interrupt Handler in protected mode (assembly)
- Video Recording
- Exception handling

### Lecture 6: System Calls in Protected Mode
- [Tutorial 6 (Slides)]()
- System Calls in protected mode (assembly)

### Lecture 7: Task in Protected Mode
- [Tutorial 7 (Slides)]()
- Task in protected mode (assembly)

### Lecture 8: Privilege-Level Protection
- [Tutorial 8 (Slides)]()

### Lecture 9: Multitasking
- [Tutorial 9 (Slides)]()
- Multitasking Program (assembly)

### Lecture 10: Kernel with C
- [Tutorial 10 (Slides)]()
- C-Kernel Program (C+Assembly)

### Lecture 11: Introduction to Paging
- [Tutorial 11 (Slides)]()
- Paging Setting (Identity Mapping)

### Lecture 12: Task-based Paging
- [Tutorial 12 (Slides)]()
- Task-based Paging (Dual Mapping)

### Lecture 13: Fundamentals of Context Switch
- [Tutorial 13 (Slides)]()
- C/Assembly Cross-Calls

### Lecture 17: Software-Based Context Switch
- [Tutorial 14 (Slides)]()
- Program with Software Context Switch

### Lecture 18: Interrupt Handling
- [Tutorial 15 (Slides)]()

### Lecture 19: Midterm Wrap Up
- [Midterm Wrap Up (Slides)]()

### Lecture 19: I/O and Terminal
- [Tutorial 16 (Slides)]()
- TTY Implementation

### Lecture 20: Exploring Nested Interrupts with TTY
- [Tutorial 17 (Slides)]()
- TTY-Interrupt Implementation

### Lecture 21: Inter-Process Communication
- [Tutorial 18 (Slides)]()
- IPC Implementation

### Lecture 22: Programming IDE Hard Disks
- [Tutorial 19 (Slides)]()

### Lecture 23: Hard Disk Drivers
- [Tutorial 20 (Slides)]()
- [Tutorial 20A (Slides)]()
- HD Driver
- [An Exemplary Bochs Configuration]()

### Lecture 24: Hard Disk Partitioning
- [Tutorial 21 (Slides)]()
- HD Partitioning

### Lecture 25: File System Fundamentals and MKFS
- [Tutorial 22 (Slides)]()
- MKFS

### Lecture 26: File System Implementation
- [Tutorial 23 (Slides)]()
- FS Implementation

### Lecture 27: Memory Management
- [Tutorial 24 (Slides)]()

### Lecture 28: Process Implementation: fork
- [Tutorial 25 (Slides)]()
- Buggy Fork

### Lecture 29: Process Implementation: exec
- [Tutorial 26 (Slides)]()
- Exec

---

## Readings & Links

- **Virtual Machine (XUbuntu IA32) and Installation Guide (Windows/macOS)**
  - VM Image Download Link: [XUbuntu VM Image (IA32)]()
  - Installation Guide on VirtualBox (Windows)
  - Installation Guide on UTM (macOS)
- **Docker-based Experimental Environment (Thanks Bensen)**
  - [Readme (by Bensen)]()
- [Intel 80386: Programmer's Reference Manual]()
- **Evolution of CPU Processing Power (YouTube Videos)**
  - [Part 1: The Mechanics of a CPU]()
  - [Part 2: Rise of the x86]()
  - [Part 3: The Origin of Modern Operating Systems]()
  - [Part 4: The 32-Bit Processor - Pipelines and Caches]()
- [Xv6, a simple Unix-like teaching operating system]()
- [Understanding the Linux Kernel, Third Edition (by Daniel P. Bovet and Marco Cesati)]()
- [Linux Interrupts: The Basic Concepts (by Mika J. Järvenpää)]()

---

## Contacting Us

**Instructor:**
- Prof. Zili Shao: [zilishao@cuhk.edu.hk](mailto:zilishao@cuhk.edu.hk)

**Tutor:**
- Zizhan Chen: [chenzz@cse.cuhk.edu.hk](mailto:chenzz@cse.cuhk.edu.hk)