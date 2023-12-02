Prime Number Finder in C++
Project Description
This repository contains a C++ application designed to efficiently find prime numbers using multithreading. The application showcases both the power of C++ in handling computation-intensive tasks and the utility of concurrent programming for performance optimization.

Key Features
- Multithreaded Design: Utilizes the multithreading capabilities of C++ to divide the workload among multiple threads, enabling faster computation by leveraging multi-core processors.

- Efficient Prime Number Checking: Implements a basic yet effective algorithm for checking prime numbers. The program excludes even numbers (except 2) and only checks up to the square root of each number to minimize unnecessary computations.

- Dynamic Thread Allocation: The number of threads spawned is dynamically determined based on the hardware's concurrency level, ensuring optimal use of available resources.

- Synchronized Output: Uses mutexes to manage concurrent access to the standard output, ensuring that the prime numbers are printed in an orderly manner without interference between threads.

- Endless Execution: The program is designed to continuously search for prime numbers, demonstrating an ongoing process of computation. Users can manually stop the execution as per their needs.

- One minute "benchmark" run. To extablish dominance over your nephews' puny CPU's. 


Compilation and Execution Instructions for C++ Script
For Debian-Based Linux
Prerequisites:

- C++ Compiler (g++): Install with sudo apt-get install g++ if not already installed.
- Compiling and Running the C++ Program:

1. Open a terminal.
2. Navigate to the directory containing the C++ file (prime_finder_multithreaded.cpp).
3. Compile the program:

```bash
g++ -o prime prime.cpp -lpthread
```

4. Run the program:

```bash
./prime
```

For Windows
Prerequisites:

- C++ Compiler: Install a C++ compiler like MinGW or Microsoft Visual C++. Ensure it's added to the system's PATH. 

Compiling and Running the C++ Program:

1. Open Command Prompt or PowerShell.
2. Navigate to the directory containing the C++ file (prime.cpp).
3. Compile the program (using MinGW as an example):

- For Command Prompt (CMD):

```cmd
g++ -o prime.exe prime.cpp -lpthread
prime.exe
```

- For Powershell:

```powershell
g++ -o prime.exe prime.cpp -lpthread
.\prime.exe
```

Note:

- These instructions assume standard installations of the necessary tools. Users might need to adjust commands based on their specific setup.
- For Windows, using a development environment like Cygwin or Windows Subsystem for Linux (WSL) can provide a more Unix-like experience.


Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change. Don't forget to update tests as appropriate.
License

This project is MIT licensed.
