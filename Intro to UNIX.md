
## What is Operating System?

- ***Definition:*** An operating system (OS) is a software program that serves as an intermediary between computer hardware and user applications, managing computer resources and providing an interface for user interaction.
- ***Key Functions:***
	1. **Resource Management**: Allocates and managers hardware resources such as CPU, memory, disk space and peripheral devices *(E.g. Printer, Monitors, Mice)*.
	2. **Process Management**: Controls execution of processes, multitasking and scheduling.
	3. **Memory Management**: Manages system memory. *(E.g. Allocating, deallocating system memory.*
	4. **Device Management**:  Controls input/output devices such as keyboards, monitors etc.
	5. **Error Handling**: Detects and handles errors occurring within the system.
	6. **Security**: Apply access control and authentication.
- ***Characteristic of an OS***:
	- **Multi-User**: Supports multiple users accessing the system concurrently. This feature is supported in UNIX and Linux.
	- **Real-Time**: Provides guaranteed response times for critical tasks
	- **Multi-Processing**: Utilised to distribute computational tasks across multiple nodes or servers, allowing each node to run multiple processes concurrently.
	- **Multi-Threading**: Optimises individual node performance by enabling concurrent task management, enhancing overall system throughput and scalability.

## UNIX Architecture

<img src="./images/UNIX Architecture.png" width="300" height="300"/>

* Hardware: The hardware provides the foundation upon which the operating system and software runs
* Kernel: The kernel allows applications to access the hardware resources without needing to understand the hardware details.
* Shell: The shell is the CLI through which the user interacts with the OS. It provides a means for the users to navigate the file system, manipulate files and run programs etc.
* Applications: These are the programs and software that users run on the OS to perform specific tasks. When a user launches an application, the shell may facilitate the process by executing the necessary commands to start the application. The application then interacts with the kernel, which manages resources and provides services to ensure the application runs smoothly.

#### How does it work?

1. When a user interacts with the computer, they input commands through the shell. For example, they might type a command to open a text editor.
2. The shell interprets the command and communicates with the kernel, requesting the necessary resources to execute the command.
3. The kernel receives the request, checks permissions, allocates resources, and performs the required operations. It may access hardware components or manage memory as needed.
4. If the command involves running an application, the kernel loads the application into memory and begins executing it.