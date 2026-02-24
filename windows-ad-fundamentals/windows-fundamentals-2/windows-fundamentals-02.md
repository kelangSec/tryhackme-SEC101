# Windows Fundamentals 2

## Overview

This room covers essential system management tools and configuration features in Windows.  
The goal is to understand how to configure system settings, monitor performance, and access advanced Windows tools for security and administration.

## 1. System Configuration and Advanced System Settings

- Access via: `Control Panel → System → Advanced system settings`  
- Configure startup and recovery options  
- Adjust environment variables  
- Manage performance settings (visual effects, processor scheduling, virtual memory)  
- Important for optimizing system performance and troubleshooting  

## 2. Change User Account Control (UAC) Settings

- User Account Control prevents unauthorized changes to the system  
- Access via: `Control Panel → User Accounts → Change User Account Control settings`  
- Levels range from “Always notify” to “Never notify”  
- Adjust according to security needs, but never disable in enterprise environments  

## 3. Computer Management

- Central hub for system administration tools  
- Components include:  
  - Disk Management → create, format, and resize partitions  
  - Event Viewer → view system and application logs  
  - Task Scheduler → automate tasks  
  - Device Manager → manage hardware and drivers  
- Useful for monitoring and managing Windows systems  

## 4. System Information

- Access via `msinfo32`  
- Provides detailed hardware and software information  
- Useful for troubleshooting, reporting, and auditing system configurations  

## 5. Resource Monitor

- Monitor system resources in real time: CPU, memory, disk, and network  
- Access via `Task Manager → Performance → Open Resource Monitor`  
- Helps detect resource-heavy processes and potential security anomalies  

## 6. Command Prompt

- Access via `cmd` or `Run → cmd`  
- Useful for executing system commands, troubleshooting, and automation  
- Common commands covered in this lab:  
  - `systeminfo` → view system configuration  
  - `ipconfig` → network configuration  
  - `whoami` → current user  
  - `tasklist` → running processes  

## 7. Registry Editor

- Access via `regedit`  
- Windows hierarchical database for system and application settings  
- Can modify startup programs, system policies, and configurations  
- Must be used with caution — incorrect changes can break the system  

## 8. Conclusion

- System configuration tools are essential for administration and security  
- UAC and registry help enforce system security  
- Resource Monitor and System Information allow performance monitoring  
- Command Prompt and Computer Management provide powerful troubleshooting capabilities  
- Mastering these tools builds a strong foundation for Windows system security  

## Screenshot

Here is the placeholder for your lab screenshot (single line, will display correctly):

![Windows Fundamentals 02 Screenshot](windows_fundamentals_02_complete.png)

Replace this with your actual screenshot once the lab is complete.

## What I Learned

- How to configure advanced system settings and optimize performance  
- Adjust User Account Control (UAC) for security  
- Use Computer Management for administration tasks  
- Access detailed system information for troubleshooting  
- Monitor CPU, memory, disk, and network usage with Resource Monitor  
- Execute commands via Command Prompt  
- Navigate and modify Windows Registry safely  
