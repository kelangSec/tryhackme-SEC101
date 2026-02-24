# Windows Fundamentals 2

## Overview

This room builds on Windows Fundamentals 1 and focuses on practical system tasks, basic networking, user accounts, and an introduction to Active Directory concepts.  

The goal is to strengthen your Windows OS skills, file system understanding, and prepare you for enterprise security environments.

## 1. File and Folder Management

You will work with files and folders to practice:

- Creating, copying, moving, and deleting files/folders  
- Understanding NTFS permissions in more detail  
- Sharing folders and setting access rights  

Proper file and folder management is critical for both system administration and security.

## 2. Basic Networking

Learn to check and troubleshoot your system’s network:

- View IP addresses: `ipconfig`  
- Ping other hosts: `ping`  
- Check active network connections: `netstat`  
- Understand local vs public IPs  

Networking basics are essential for analyzing traffic and detecting misconfigurations.

## 3. User Accounts and Groups

Windows user and group management:

- Creating and managing user accounts  
- Understanding groups and group membership  
- Switching between users and logging in/out  

Managing permissions properly reduces security risks in enterprise environments.

## 4. Command Line / PowerShell Basics

Command-line tools covered:

- Navigate directories: `cd`, `dir`  
- File manipulation: `copy`, `move`, `del`  
- Check system information: `systeminfo`  
- Basic PowerShell commands for users, groups, and processes  

Command-line skills are critical for automation, troubleshooting, and security tasks.

## 5. Task Manager and Services

Use Task Manager to:

- Monitor running processes  
- Manage startup programs  
- Stop or start services (if allowed in the lab)  

Understanding processes and services is key to system monitoring and incident response.

## 6. Introduction to Active Directory Basics

Active Directory (AD) concepts covered:

- What AD is and its purpose in enterprises  
- Domain controllers, domains, and users  
- Basic AD concepts: organizational units (OUs), accounts, and groups  

AD is widely used in enterprise environments, and understanding it is foundational for security work.

## 7. Key Security Concepts

- Proper file/folder permissions prevent unauthorized access  
- Privilege levels matter for system and network security  
- Network information is valuable for security analysis  
- User and group management reduces potential attack vectors  

## 8. Useful Commands

### View IP Configuration

ipconfig


### Ping a Host

ping <hostname or IP>


### Check Active Connections

netstat -an


### List Users (PowerShell)

Get-LocalUser


### List Groups (PowerShell)

Get-LocalGroup


## Screenshot



![Windows Fundamentals 02 Screenshot](windows_fundamentals_02_complete.png)



## What I Learned

- Managing files, folders, and NTFS permissions  
- Basic Windows networking commands and troubleshooting  
- Creating and managing user accounts and groups  
- Navigating and using Windows Command Line and PowerShell  
- Monitoring processes, startup programs, and services  
- Introduction to Active Directory concepts  
- Understanding key security implications in a Windows environment
