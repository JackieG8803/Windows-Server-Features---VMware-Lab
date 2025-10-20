# Windows Server Features Lab (VMware)

This project explores the deployment and management of Windows Server in a VMware virtualized environment. The lab covers foundational server tasks, including installation, configuration, remote management, web hosting, routing, file services, software RAID, and shadow copy.

## 📚 Project Overview

- **Platform:** VMware Workstation/Player
- **OS:** Windows Server (Standard with GUI)
- **Client:** Windows machine or VM

## 🗂️ Lab Outline

1. **Setting Up Virtual Machines**
    - Created new VM for Windows Server.
    - Configured disk sizes and network adapters (NAT/VMnet3).
    - Performed a fresh install and initial configuration.
    - <img width="747" height="727" alt="image" src="https://github.com/user-attachments/assets/9cb159e9-4ac3-48ee-9762-9e842423c189" />


2. **Initial Login & Server Manager Tour**
    - Explored Server Manager Dashboard.
    - Configured server name for clarity and management.
    - <img width="975" height="458" alt="image" src="https://github.com/user-attachments/assets/a79f2735-a58f-4c94-a6fe-6539eb582308" />



3. **Exploring Server Roles**
    - Reviewed available roles (AD DS, DHCP, DNS, RDS, IIS, etc.).
    - Documented 5 roles and their descriptions.

        | Role                         | Description                                   |
        |------------------------------|-----------------------------------------------|
        | Active Directory Domain Services | Centralized domain management                |
        | DHCP Server                  | Auto assigns IP addresses to network devices  |
        | DNS Server                   | Translates domain names to IPs                |
        | Remote Desktop Services      | Enables remote desktop capabilities           |
        | Web Server (IIS)             | Hosts websites and web applications           |

4. **Exploring Server Features**
    - Examined extra features (Bitlocker, GPO, Load Balancing, etc.).

        | Feature                     | Description                                   |
        |-----------------------------|-----------------------------------------------|
        | Bitlocker Drive Encryption  | Encrypts drives for enhanced security         |
        | Group Policy Management     | Centralizes configuration via GPOs            |
        | Network Load Balancing      | Distributes traffic for high availability     |
        | Remote Assistance           | Enables remote support for users              |
        | SMTP Server                 | Sends and receives emails                     |

5. **Remote Desktop Setup**
    - Enabled and tested RDP from a client machine.
    - <img width="975" height="429" alt="image" src="https://github.com/user-attachments/assets/650fe001-e66d-4ad8-9c52-cfabd8e2bc21" />
    - <img width="975" height="423" alt="image" src="https://github.com/user-attachments/assets/dd6bf2af-58e9-4218-9b51-e79dd241eb3b" />



6. **Installing and Testing IIS**
    - Added Web Server (IIS) role with FTP services.
    - Tested default web page in a client browser.
    - Published a custom HTML page.
    - <img width="2558" height="1390" alt="image" src="https://github.com/user-attachments/assets/a36c3089-871a-4388-b50b-47fa4bb1405e" />


7. **Routing and Remote Access (RRAS)**
    - Enabled server to function as NAT router and VPN server.
    - Set up subnets, IPs, and connected a client via VPN.

8. **File Services: FSRM Quotas and Screening**
    - Installed File Server Resource Manager.
    - Set storage quotas and file screening rules.
    - Tested and triggered alerts for file screening.

9. **Shadow Copy**
    - Enabled Shadow Copy on C: drive.
    - Demonstrated file recovery by restoring deleted files.
    - <img width="2568" height="1400" alt="image" src="https://github.com/user-attachments/assets/82ae3e8c-dacf-4620-ab8e-434ca60a61ac" />


## 💡 Key Concepts Demonstrated

- Server deployment and initial setup in VMware.
- Hands-on practice with Windows Server roles and features.
- Remote management and security (RDP, VPN).
- Web service and file service configuration.
- Automation via Server Manager and awareness of PowerShell options.

## 📝 Learning Outcomes

- Gained hands-on experience with essential Windows Server tools and configurations.
- Practiced troubleshooting, security, and storage management in an enterprise context.
- Improved confidence managing servers in virtualized lab settings.

## 🔗 Portfolio

Return to my main portfolio: [JackieG8803 IT Portfolio](https://github.com/JackieG8803)

---
