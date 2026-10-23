# Enterprise Active Directory & Windows Server Infrastructure Lab

**Technologies:** Windows Server 2025 | Active Directory | Windows 11 | VMware | NTFS Permissions | File Services

## Project Overview

Designed and deployed a virtualized Windows infrastructure environment to simulate core enterprise IT operations, including centralized identity administration, domain authentication, network file sharing, and access control.

The environment consists of two VMware virtual machines:

- **Windows Server 2025:** Configured as an Active Directory Domain Controller and Windows File Server.
- **Windows 11:** Domain-joined workstation used to validate domain connectivity, authentication, and file access permissions.

## 1. Active Directory Deployment & Administration

- Deployed Active Directory Domain Services (AD DS) and promoted Windows Server 2025 to a Domain Controller.
- Established a centralized directory environment for managing domain identities and resources.
- Created and structured Organizational Units (OUs) and user accounts to simulate enterprise identity administration.

**Active Directory Configuration**

![Active Directory](screenshots/02-domain-controller.png)

**Organizational Units & User Management**

![Organizational Units](screenshots/03-organizational-units.png)

![Domain Users](screenshots/04-domain-users.png)

## 2. Windows 11 Domain Integration

- Provisioned a Windows 11 virtual machine and configured communication with the Domain Controller.
- Successfully joined the workstation to the Active Directory domain.
- Validated domain connectivity and access to shared network resources.

**Domain-Joined Workstation**

![Domain Integration](screenshots/05-windows11-domain.png)

## 3. File Server Configuration & Access Control

- Configured Windows file-sharing services on the Windows Server 2025 virtual machine.
- Established shared directories and assigned user-specific access permissions.
- Configured file-sharing and NTFS permissions to enforce authorized resource access.
- Conducted access validation from the Windows 11 client to verify that authorized users received appropriate access and restricted users were denied.

**File Server Configuration**

![File Server](screenshots/07-file-server.png)

**File Permissions**

![File Permissions](screenshots/09-file-permissions.png)

**Access Control Validation**

![Authorized Access](screenshots/10-authorized-access.png)

![Access Denied](screenshots/11-access-denied.png)

## Technical Competencies Demonstrated

- **Systems Administration:** Windows Server deployment, configuration, and management.
- **Identity & Access Management:** Active Directory, domain authentication, user provisioning, and organizational unit administration.
- **Infrastructure & Networking:** VMware virtualization, client-server connectivity, and domain integration.
- **Security Administration:** NTFS permissions, shared resource authorization, and access control validation.
- **Troubleshooting:** Windows networking, domain connectivity, and permission verification.

## Project Outcome

Successfully implemented a functional Windows domain environment integrating centralized identity management, a domain-joined client workstation, and permission-controlled network file sharing.

Validated system functionality through domain integration and user access testing, demonstrating practical experience with enterprise Windows infrastructure, identity administration, and security controls.
