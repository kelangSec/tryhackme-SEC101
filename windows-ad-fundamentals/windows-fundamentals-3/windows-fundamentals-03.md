# Windows Fundamentals 3

## Overview

This room expands on Windows Fundamentals 1 and 2, focusing on advanced Windows tools, system troubleshooting, and basic security practices.  

The goal is to gain deeper understanding of Windows processes, services, event logs, and more complex file and user management tasks.

## 1. Advanced File and Folder Management

- Using file properties and advanced NTFS permissions  
- Understanding inherited permissions  
- Configuring shared folders with specific access rights  
- Mapping network drives  

These skills are crucial for enterprise environments and secure file access.

## 2. Services and Processes

- Viewing running services: `services.msc`  
- Starting and stopping services  
- Monitoring processes using Task Manager or PowerShell: `Get-Process`  
- Identifying critical system processes  

Understanding services and processes is important for troubleshooting and security investigations.

## 3. Event Viewer

Event Viewer allows monitoring of system and security events:

- Access Event Viewer: `eventvwr.msc`  
- Review application, system, and security logs  
- Identify warnings, errors, and information events  

Event logs are essential for auditing and detecting suspicious activity.

## 4. PowerShell Advanced Commands

- Listing all processes: `Get-Process`  
- Managing services: `Get-Service`, `Start-Service`, `Stop-Service`  
- Checking user group memberships: `Get-LocalGroupMember <GroupName>`  
- Exporting information: `Export-Csv`  

PowerShell is a powerful tool for automation, security, and system administration.

## 5. Task Scheduler

- Automating tasks using Task Scheduler  
- Scheduling scripts or maintenance tasks  
- Managing existing scheduled tasks  

Automation increases efficiency and is commonly used in enterprise environments.

## 6. Key Security Concepts

- Proper file and folder permissions prevent unauthorized access  
- Monitoring services and processes helps detect anomalies  
- Event logs are critical for security auditing  
- PowerShell can be used for administration and also abused by attackers  

## 7. Useful Commands

### List All Processes

Get-Process


### View Services

Get-Service


### Event Logs

eventvwr.msc


### Check Group Members

Get-LocalGroupMember <GroupName>


## Screenshot



![Windows Fundamentals 03 Screenshot](windows_fundamentals_03_complete.png)



## What I Learned

- Advanced file and folder management  
- Monitoring and managing Windows services and processes  
- Using Event Viewer for auditing  
- Automating tasks with Task Scheduler  
- Applying key security practices for system monitoring and protection
