# Windows Fundamentals 1

## Overview

This room introduces the foundational concepts of the Windows operating system.  
It focuses on understanding Windows editions, the graphical user interface (GUI), the NTFS file system, user accounts, User Account Control (UAC), and essential built-in system tools.  

Windows is widely used in enterprise environments, making it a critical skill for cybersecurity professionals.

## 1. Introduction to Windows

In this lab, a Windows virtual machine (VM) is provided to explore and interact with the operating system.  

The goal is to become familiar with the Windows environment, system navigation, and basic configuration tools.

## 2. Windows Editions

Common Windows editions include:

- Windows Home  
- Windows Pro  
- Windows Enterprise  
- Windows Server  

Enterprise and Server editions are commonly used in corporate environments.  
Some security features (e.g., BitLocker encryption) are only available in Pro or Enterprise editions.

## 3. The Windows Desktop (GUI)

Key components of the Windows GUI include:  

- Desktop  
- Start Menu  
- Taskbar  
- Notification Area  
- File Explorer  

File Explorer is used to navigate files and folders within the system.

## 4. The Windows File System

Windows primarily uses **NTFS (New Technology File System)**.  

NTFS features include:  

- File and folder permissions  
- Encryption (EFS)  
- Compression  
- Auditing  
- Large file support  

NTFS permissions are important in enterprise security and privilege management.

## 5. Important System Directories

Common directories include:  

- `C:\Windows` → Core OS files  
- `C:\Windows\System32` → Critical system executables and libraries  
- `C:\Users` → User profile folders  
- `C:\Program Files` → Installed applications  
- `C:\Program Files (x86)` → 32-bit programs on 64-bit systems  

Understanding these directories is important for system investigation and security analysis.

## 6. User Accounts

Types of user accounts in Windows include:  

- Administrator  
- Standard User  
- Guest  

Administrators have full system privileges; standard users have limited permissions.  
User privilege levels are critical in preventing unauthorized changes.

## 7. User Account Control (UAC)

User Account Control helps prevent unauthorized changes to the system.  

When a program requires elevated privileges, Windows prompts the user for approval.  

UAC reduces the risk of malware executing with administrator privileges.

## 8. Control Panel & Settings

The Control Panel allows users to:  

- Manage user accounts  
- Configure network settings  
- Adjust system configurations  
- Uninstall programs  

It is a central management interface in Windows.

## 9. Task Manager

Task Manager is used to:  

- View running processes  
- Monitor CPU and memory usage  
- End unresponsive applications  
- Manage startup programs  

Shortcut to open Task Manager:
Ctrl + Shift + Esc


## 10. Useful Commands

### View System Information

systeminfo


### View Current Logged-in User

whoami


### Open System Information Tool

msinfo32


## Screenshot

Below is a placeholder for the lab completion screenshot:

![Windows Fundamentals 01 Complete](windows_fundamentals_01_complete.png)

Replace this with your actual screenshot once the lab is complete.

## Key Security Insights

- Most enterprise environments rely on Windows systems.  
- Misconfigured permissions can lead to privilege escalation.  
- Understanding default directories helps during investigations.  
- UAC is a basic but important security control.

## What I Learned

- How Windows editions differ  
- How the Windows GUI is structured  
- The importance of NTFS and file permissions  
- How user accounts and privilege levels work  
- The role of UAC in system protection  
- How to use basic Windows system tools  

This room builds the foundation required for deeper Windows security topics and Active Directory environments.
