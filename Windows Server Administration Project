# Windows Server 2016 Domain Environment Project (MCSA)

## 📌 Overview
This project demonstrates a complete enterprise Windows Server environment built using VMware Workstation. It includes Active Directory, DNS, DHCP, Group Policies, and Windows 10 client integration.

---

## 🖥️ Environment
- VMware Workstation
- Windows Server 2016
- Windows 10 Client Machine

---

## 🌐 Domain Configuration
- Created domain: **Tawwab**
- Promoted server to Domain Controller
- Static IP configured: **192.168.2.1**
- DNS role installed and configured
- Firewall disabled for lab environment

---

## 🏢 Active Directory Structure
- Created Organizational Units (OUs):
  - Human Resources (HR)
  - Information Technology (IT)
  - Sales
- Created users and groups for each OU
- Configured:
  - Logon time restrictions (Sunday–Thursday, 12 PM – 9 PM)
  - Password policies (force change at first login)
  - Disabled password change for specific users
  - Disabled specific user accounts

---

## 📁 File Server Configuration
- Created main shared folder: **OHI (D:\OHI)**
- Subfolders with permissions:
  - HR → HR Group only
  - IT → IT Group only
  - Sales → Sales Group only
- Enabled:
  - File Encryption (EFS)
  - Folder Compression
  - Shadow Copy on D: drive

---

## 💾 Storage Management
- Configured Disk Quota:
  - 1 GB per user
  - 5 GB for HR department

---

## 🔐 Group Policy (GPO)
- HR: Block external storage devices
- IT: Disable Control Panel access
- Sales: Remove Run command
- Domain policy:
  - Password expiration: 30 days
  - Password complexity: disabled

---

## 👤 Administration
- Created additional Domain Admin account:
  - "Tawwab Admin"

---

## 💻 Client Configuration
- Installed Windows 10 on VMware
- Configured IP and DNS
- Joined successfully to domain
- Configured DHCP server:
  - Range: 192.168.2.2 – 192.168.2.100
  - DHCP reservation for PC1
- Installed and configured WDS (Windows Deployment Services)

---

## 🚀 Advanced Features
- Remote Desktop Services enabled
- Remote access tested using domain admin account

---

## 🎯 Purpose
This project simulates a real enterprise IT infrastructure for domain management, user control, security policies, and network services.
