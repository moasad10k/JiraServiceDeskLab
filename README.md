# Jira Service Management – IT Support Service Desk Lab

## Overview
A hands-on IT Support Service Desk lab built using Jira Service Management to simulate real-world help desk scenarios. This project covers incident management, service requests, troubleshooting, ticket prioritisation, customer communication, documentation, and resolution verification.

I worked through five simulated support tickets, investigating issues, performing troubleshooting, documenting findings, communicating with users, and resolving each ticket.

## Environment & Tools
- Jira Service Management
- Windows 11 (Client workstation)
- Windows Server 2022
- Oracle VirtualBox
- Active Directory

## Tickets Completed

### 1. INC-001 – User Unable to Log In
**Priority:** High | **Type:** Incident

**Issue:** User unable to log in to their workstation using their company account.

**Troubleshooting:**
- Investigated the user account in Active Directory.
- Identified that the account was disabled.
- Re-enabled the account on the domain controller.
- Tested login from CLIENT1.

**Resolution:** Re-enabled the account and successfully verified user login.

[View Screenshots](screenshots/01-user-unable-to-login/)

---

### 2. INC-002 – No Internet Connectivity
**Priority:** High | **Type:** Incident

**Issue:** Workstation unable to access the internet.

**Troubleshooting:**
- Checked the workstation's network connectivity.
- Identified that the network adapter was disconnected.
- Reconnected the network adapter.

**Resolution:** Restored the network connection by reconnecting the adapter.

[View Screenshots](screenshots/02-no-internet-connectivity/)

---

### 3. INC-003 – Computer Running Slowly
**Priority:** Medium | **Type:** Incident

**Issue:** Workstation experiencing poor performance and high CPU usage.

**Troubleshooting:**
- Used Task Manager to investigate CPU utilisation, which was reaching 100%.
- Reviewed running applications and Startup Apps.
- Identified two third-party antivirus programs running simultaneously.
- Uninstalled both third-party antivirus programs.
- Disabled SysMain.
- Ran CHKDSK to check the system drive.

**Resolution:** CPU utilisation decreased from 100% to approximately 30% following the troubleshooting steps.

[View Screenshots](screenshots/03-computer-running-slowly/)

---

### 4. SR-001 – Shared Folder Access
**Priority:** Medium | **Type:** Service Request

**Issue:** User unable to access a shared folder containing files required for work.

**Troubleshooting:**
- Created and configured a shared folder on Windows Server.
- Reviewed the folder's sharing permissions.
- Identified that the test user did not have the required access.
- Added the user to the folder's sharing permissions.
- Verified access from CLIENT1.

**Resolution:** Successfully accessed the shared folder and opened the test file from the client workstation.

[View Screenshots](screenshots/04-shared-folder-access/)

---

### 5. SR-002 – Software Installation Request
**Priority:** Low | **Type:** Service Request

**Issue:** User requested Notepad++ for editing and viewing text files.

**Actions Performed:**
- Reviewed the software installation request.
- Downloaded Notepad++ onto CLIENT1.
- Installed the application.
- Launched the application and verified that it was working.

**Resolution:** Notepad++ installed successfully and its functionality was verified.

[View Screenshots](screenshots/05-software-installation/)

---

## Skills Demonstrated

- IT Support and Service Desk ticket management
- Incident management and service request handling
- Ticket prioritisation
- Troubleshooting and issue resolution
- Active Directory user account management
- Windows 11 workstation support
- Network connectivity troubleshooting
- Shared folder and access permissions
- Software installation and verification
- Task Manager and system performance troubleshooting
- Customer communication and ticket updates
- Internal documentation and resolution notes
- Ticket lifecycle management

## Ticket Lifecycle

Followed a structured Service Desk workflow throughout the lab:

1. Ticket submission
2. Priority assignment
3. Investigation
4. Internal documentation
5. Customer communication
6. Troubleshooting
7. Verification
8. Resolution and closure

## Project Outcome

Completed five simulated IT Support tickets using Jira Service Management, covering common help desk scenarios involving account access, connectivity issues, system performance, shared folder permissions, and software installation.

This project provided hands-on practice with Service Desk workflows, technical troubleshooting, user communication, and documenting support activities from initial request through resolution.
