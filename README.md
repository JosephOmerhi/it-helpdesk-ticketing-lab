# IT Help Desk Ticketing & Troubleshooting Lab

### osTicket | Windows 11 | Networking | Application Support

## Project Overview

This project demonstrates the installation, configuration, and operation of a simulated IT Help Desk environment using **osTicket 1.18.4**.

The environment represents a fictional organization called **Omerhi Technologies** and simulates real-world IT support workflows, including incident management, ticket prioritization, troubleshooting, documentation, customer communication, and ticket resolution.

The lab was built to develop practical skills relevant to **IT Support Technician, Help Desk Analyst, Desktop Support, and Technical Support Specialist** positions.

## Technologies Used

- **osTicket 1.18.4** — IT service ticket management
- **XAMPP** — Local Apache, PHP, and MySQL/MariaDB environment
- **Windows 11** — Workstation and troubleshooting environment
- **Command Prompt** — Network diagnostics
- **PowerShell** — Network configuration and connectivity testing
- **GitHub** — Project documentation and portfolio

## Help Desk Configuration

Configured three support departments:

- IT Help Desk
- Network Support
- Application Support

Created a simulated support agent, configured ticket assignments, and managed incidents through the ticket lifecycle.

## Simulated Support Incidents

### 1. Windows Workstation Login Failure

**Ticket:** #178405  
**Department:** IT Help Desk

Simulated investigation of a workstation login issue, including account access troubleshooting, a password reset scenario, internal documentation, and customer communication.

### 2. Network Connectivity and DNS Troubleshooting

**Ticket:** #424789  
**Department:** Network Support

Practised real network diagnostic commands on a local Windows workstation, including:

- `ipconfig /all`
- `ping`
- `nslookup`
- `ipconfig /flushdns`
- `Get-DnsClientServerAddress`
- `Test-NetConnection`

Documented a separate simulated DNS configuration failure and its resolution.

### 3. Microsoft Outlook Synchronization Failure

**Ticket:** #300645  
**Department:** Application Support

Simulated an Outlook desktop synchronization issue involving Work Offline mode, mailbox connectivity checks, corrective actions, verification, and customer-facing resolution.

## Skills Demonstrated

- IT incident and ticket lifecycle management
- Ticket prioritization and assignment
- Windows workstation troubleshooting
- TCP/IP networking and DNS diagnostics
- PowerShell and Command Prompt
- Application support fundamentals
- Technical documentation
- Customer communication
- Incident resolution and closure

## Lab Environment

The osTicket system was deployed locally using XAMPP on a Windows workstation.

All employee accounts, support scenarios, and incident resolutions are fictional. Real network diagnostic exercises were performed separately on the lab workstation.

## Project Status

**Completed:** Initial osTicket setup, support department configuration, simulated agent setup, and three documented support incidents.

**Future Improvements:** Add screenshots, detailed incident case studies, a setup guide, and additional troubleshooting scenarios.

---

*This project is an independent hands-on IT support training lab and does not represent production help desk employment.*


## Project Screenshots

### Completed IT Support Tickets

The screenshot below shows three simulated IT support incidents successfully documented and closed in osTicket:

- **Ticket #178405:** Windows Workstation Login Failure
- **Ticket #424789:** Network Connectivity and DNS Troubleshooting
- **Ticket #300645:** Microsoft Outlook Synchronization Failure

![Closed IT Support Tickets](screenshots/closed-tickets.png)
