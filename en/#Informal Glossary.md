Warning: Unlike a full length glossary, this informal glossary is skips on details and provides a simplified and accessible explanation of each term. For more information and details use your favorite web search engine.

## What is the kernel?
The kernel is central part of the operating system that manages processes, resources (including memory) and hardware input-output devices. User programs interact with the kernel by making system calls.

Learn more:
[[http://en.wikipedia.org/wiki/Kernel_%28operating_system%29]]

## What is a process?

A process is an instance of a program that is running on a machine. There can be multiple processes of the same program. For example, you and I might both be running 'cat' or 'gnuchess'

A process contains the program code and modifiable state information such as variables, signals, open file descriptors for files, network connections and other system resources which are stored inside the process's memory. An operating system also stores meta-information about the process which is used by the system to manage and monitor the process's activity and resource use.

Learn more:
[[http://en.wikipedia.org/wiki/Process_%28computing%29]]

## What is virtual memory?
Processes running on your smart phone and laptop use virtual memory: Each process is isolated from other processes and appears to get complete access to all possible memory addresses! In reality only a small fraction of the process's address space is mapped to physical memory and the actual amount of physical memory allocated to a process can change over time and be paged out to disk, re-mapped and securely shared with other processes. Virtual memory provides significant benefits including strong process isolation (security), resource and performance benefits (simplified and efficient physical memory use) that we will discuss later. 

Learn more:
[[http://en.wikipedia.org/wiki/Virtual_memory]]
