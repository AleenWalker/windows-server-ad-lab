# Windows Server Active Directory Lab

## Overview
Hands-on Active Directory lab designed to simulate a small-to-medium business environment.  
This project demonstrates practical system administration skills including domain setup, user management, group policies and file server permissions.

---

## Lab Environment
- Windows Server 2022 (Domain Controller & File Server)
- Windows 10 Client
- Active Directory Domain Services (AD DS)
- DNS
- NTFS & SMB File Sharing

---

## Network Diagram
![Network Diagram](diagrams/ad-lab-network-diagram.png)

---

## Implemented Features

### Active Directory
- Domain creation and configuration
- Organizational Units (OUs)
- User and group management
- Security groups

### Group Policy Objects (GPO)
- Password policies
- User restrictions
- Drive mapping
- Security settings

### File Server
- NTFS permissions
- Shared folders
- Role-based access control

### Automation
- PowerShell scripts for common administrative tasks

---

## PowerShell Scripts
| Script | Description |
|------|------------|
| create-users-bulk.ps1 | Bulk user creation |
| reset-password.ps1 | Reset user passwords |
| list-disabled-users.ps1 | List disabled AD users |

---

## Key Skills Demonstrated
- Active Directory administration
- Windows Server management
- Access control and permissions
- Automation with PowerShell
- Troubleshooting and documentation>)