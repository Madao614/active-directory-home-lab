# Active Directory Home Lab

## Overview

This repository documents my hands-on Active Directory Home Lab built using Windows Server 2022 and VirtualBox.

The goal of this lab is to gain practical experience with Active Directory administration, user and group management, Organizational Units (OUs), Group Policy, and common helpdesk tasks performed in enterprise environments.

---

## Lab Environment

### Technologies Used

* Windows Server 2022 Standard Evaluation (Desktop Experience)
* Active Directory Domain Services (AD DS)
* Group Policy Management
* VirtualBox
* Windows Networking

### Domain Information

* Domain Name: `corp.local`

---

## Day 1 Objectives

### Static IP Configuration

Configured a static IPv4 address on the Windows Server virtual machine to provide a stable networking foundation required for Active Directory services.

### Active Directory Domain Services Installation

* Installed the Active Directory Domain Services (AD DS) role
* Added required management tools
* Verified successful installation

### Domain Controller Deployment

* Promoted the server to a Domain Controller
* Created a new forest
* Created the domain `corp.local`

### Organizational Units (OUs)

Created the following Organizational Units:

* IT
* Sales
* HR

### User Management

Created test user accounts within the domain:

* Ahmed Hassan
* Sara Khalid
* Omar Farooq
* Lina Mahmoud
* Fatima Noor

### Security Groups

Created and managed security groups including:

* IT-Admins
* IT-Support
* Sales-Team
* HR-Team

### Helpdesk Administration Tasks

Practiced common Active Directory support tasks:

* Password resets
* Account unlocks
* Account disabling
* Moving users between Organizational Units

### Group Policy Configuration

Configured a password policy to enforce a minimum password length requirement across the domain.

---

## Skills Demonstrated

* Active Directory Administration
* Windows Server Management
* User and Group Management
* Organizational Unit Design
* Group Policy Management
* Domain Controller Deployment
* Identity and Access Management (IAM)
* Basic Helpdesk Operations
* Windows Networking Fundamentals

---

## Screenshots

Screenshots for each phase of the lab are available in the `Day1/Screenshots` directory.

Examples include:

* Static IP Configuration
* AD DS Installation
* Domain Creation
* Organizational Units
* User and Group Management
* Helpdesk Tasks
* Group Policy Configuration

---

## Repository Structure

```text
active-directory-home-lab/
│
├── README.md
│
├── Day1/
│   ├── Active_Directory_Home_Lab_Day1.pdf
│   │
│   └── Screenshots/
│       ├── 01-static-ip.png
│       ├── 02-adds-installation.png
│       ├── 03-domain-creation.png
│       ├── 04-ous.png
│       ├── 05-users-groups.png
│       ├── 06-helpdesk-tasks.png
│       └── 07-group-policy.png
```

---

## Future Improvements

Planned additions to this lab include:

* Windows 10/11 Domain Client
* Domain Join Process
* Shared Folders and Permissions
* Advanced Group Policies
* DNS Configuration
* DHCP Services
* Sysmon Deployment
* SIEM Integration
* Windows Event Forwarding
* Active Directory Security Monitoring

---

## Author

Ahmed Salahudin

Cybersecurity Professional with hands-on experience in Windows Server administration, networking, and Active Directory environments.
