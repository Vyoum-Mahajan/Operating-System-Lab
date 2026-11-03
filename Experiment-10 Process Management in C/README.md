# Process Management in C

## Aim

To understand basic process management in Linux using C system calls
such as `fork()`, `getpid()`, `getppid()` and `wait()`.

## Requirements

-   Ubuntu/Linux
-   GCC compiler
-   C programming language
-   Text editor or terminal

## Programs Included

1.  **PID Demonstration:** Uses `getpid()` to display the current
    process ID.
2.  **Parent-Child Synchronization:** Uses `fork()` to create a child
    process and `wait()` to make the parent wait for it.

## How to Run

Install GCC if required:

``` bash
sudo apt update
sudo apt install build-essential
```

Compile a program:

``` bash
gcc filename.c -o output
```

Run it:

``` bash
./output
```

Replace `filename.c` with the C source file name and `output` with the
executable name.

## Concepts Covered

-   Process and Process ID (PID)
-   Parent and child processes
-   Process creation using `fork()`
-   Process identification using `getpid()` and `getppid()`
-   Process synchronization using `wait()`
-   Introduction to orphan and zombie processes

## Conclusion

This project demonstrates how Linux creates, identifies and synchronizes
processes using basic C system calls.
