# Task 3.1 -Explore your operating System
| Information Explored | What It Tells You |  Observation (Privacy-Safe) |
|---|---|---|
| Operating system / system details | Identifies the OS name, version and system architecture. | OS: macOS, Version: 27.2, Architecture: arm64  |
| Current account identity | Identifies the currently active user account. | showed my name  |
| Available and used storage | Shows total, used and available storage space. | Total: 460Gi, Used:93Gi , Available: 330Gi |
| System activity snapshot | Shows running processes and system resource usage. | Observed CPU, memory and process information. |

# Task 3.2 - Understand process
1. What is a process?

   ans: A process is a program that is currently executing.

2. What does the PID column represent?

   ans:PID stands for Process ID. It is a numerical identifier assigned to each     
   running process.

3. Give two examples of processes that may be running on your computer.
   
   ans : VS CODE 
         Finder


# Task 3.3 - Understand paths and permissions

### 1. Absolute Path vs Relative Path

| Absolute Path | Relative Path |
|:---:|:---:|
| Specifies the complete location of a file or folder. | Specifies a location relative to the current directory. |
| Starts from the root directory /. | Depends on the current working directory. |
| Example: /Users/yasharya/Desktop/digital_detective-8525/mission-03-operating-system | Example: mission-03-operating-system |

### 2. File permissions (observation)

1.-rw-r--r--  1 yasharya  staff     0 Nov 11 11:53 README.md
- File permissions:
    - owner = read and write
    - group= only read
    - others= only read

2. -rw-r--r--@ 1 yasharya  staff  1471 Nov 15 14:11 mission3.md  
- File permissions:
    - Owner: Read and Write only.
    - Group: Read only.
    - Others: Read only.

# Task 3.4 -EXPALIN operating-system responsibilities

| OS Responsibility | Explanation | Example |
|:---|:---|:---|
| Process management | Manages running programs and allocates CPU time to them. | Running Chrome and VS Code simultaneously. |
| Memory management | Allocates and manages RAM for different programs. | Giving Chrome memory to run multiple tabs. |
| Device management | Controls and manages connected hardware devices. | Managing keyboard, mouse and printer. |
| File management | Organises, stores and manages files and folders. | Creating, renaming and deleting files. |
| User interface / shell | Provides a way for users to interact with the computer. | Using macOS desktop or Terminal |
| Security and permissions | Protects files and system resources by controlling user access. | Allowing only authorised users to modify a file. |
