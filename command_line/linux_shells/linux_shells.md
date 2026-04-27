# 🐧 Linux Shells – Notes

## Introduction to Linux Shells
Linux shells are interfaces that allow users to interact with the operating system using commands. The shell acts as a bridge between the user and the Linux kernel, interpreting commands and returning output.

---

## How to Interact with a Shell
- Users interact with the shell through the terminal  
- Commands are typed and executed line by line  
- The shell returns output or errors based on the command  

Example interaction:
ls → lists files in the current directory  
pwd → shows current directory  
whoami → shows current user  

---

## Types of Linux Shells
There are several types of Linux shells:

- Bash (Bourne Again Shell) → most common and default on many systems  
- sh (Bourne Shell) → original Unix shell  
- zsh (Z Shell) → advanced shell with customization features  
- ksh (Korn Shell) → used in scripting and system tasks  

Bash is the most widely used in cybersecurity and Linux environments.

---

## Shell Scripting and Components
Shell scripting allows automation of tasks using a file containing commands.

Basic components of a shell script:
- Shebang (#!/bin/bash) → defines the shell  
- Commands → instructions executed by the shell  
- Variables → store data  
- Comments → explain script logic  

Example structure:
#!/bin/bash  
echo "Hello World"

Shell scripts are used for automation, system tasks, and repetitive operations.

---

## The Locker Script
The locker script is an example of a simple shell script used to demonstrate:
- File access control  
- Conditional logic  
- User interaction  

It typically restricts or manages access based on conditions defined in the script.

---

## Practical Exercise
- Identify different shell types on a system  
- Run basic shell commands  
- Execute a simple shell script  
- Observe how input is processed by the shell  
- Practice navigation and file interaction using terminal commands  

---

## Key Takeaways
- The shell is the interface between user and operating system  
- Bash is the most commonly used Linux shell  
- Shell scripting is used for automation and efficiency  
- Understanding shells is essential for cybersecurity and system administration  
- Practical usage improves command-line proficiency  

---

## Screenshot

![complete](linux_shells_done.png)

> Screenshot shows completion of Linux Shells room on TryHackMe

---

## Final Conclusion
Linux shells are a core part of system interaction. Mastering shell usage and scripting improves efficiency, automation capability, and overall understanding of Linux systems in real-world environments.
