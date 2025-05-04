# it-support-lab

Simulated IT support lab using a Windows Server 2019 VM hosted in Azure. It includes the setup and configuration of Active Directory, DNS, domain joining, user account management, and real-world troubleshooting tasks to simulate a professional help desk environment.

## Current Progress

The lab setup began with configuring core server infrastructure:

- **Windows Server 2019 VM Initialization**: Deployed and connected via Azure remote desktop
- **Server Manager Configuration**: Performed initial setup through Server Manager dashboard
- **Static IP Address Configuration**: Converted dynamic IP to static via IPv4 properties for DHCP compatibility
- **Network Configuration Validation**: Used `ipconfig` before and after to verify IP changes
- **DHCP Server Role Installation**: Installed DHCP Server role with necessary management tools
- **Screenshots & Documentation**: Captured all configuration steps for transparency and future review

## Upcoming Features

- Active Directory Domain Services setup
- DNS Server configuration
- Domain join of Windows clients
- User account and OU management
- Simulated support tickets & troubleshooting scenarios

This lab is a work in progress and aims to demonstrate not only server setup, but practical IT support workflows in a controlled, reproducible environment.
