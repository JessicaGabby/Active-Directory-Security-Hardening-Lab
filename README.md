# Active-Directory-Security-Hardening-Lab
This project focuses on building and securing a Windows Active Directory environment. I deployed a domain controller, joined a Windows 10 workstation, and implemented security baselines using Group Policy. The goal was to simulate enterprise identity management and strengthen authentication controls.

 ## Technologies Used:
- Windows Server 2022
- Windows 10 Pro
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy Management
- Event Viewer
- PowerShell
- VirtualBox 

### Domain Controller (DC01)
- Promoted to AD DS
- DNS installed
- Domain: jessica.local

### Organizational Units
- _Jessica-Admins
- _Jessica-Computers
- _Jessica-Users
- Corp Computers
- Corp Users
- Jessica Corp

### Users Created
- Helpdesk User
- Jess User
- Test User

### Groups 
- Created basic AD groups

### Workstation Joined to Domain
- Windows 10 machine joined to jessica.local

### Group Policy
Applied security baselines:
- Password complexity
- Minimum length
- Account lockout
- USB blocking
- Local admin restrictions

### Validation
- gpupdate /force
- Event Viewer logs
- Login tests

