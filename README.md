# Linux-Network-Services-Deployment-and-Administration

## Project Overview

This project demonstrates the deployment, configuration, and testing of essential Linux network services in a virtualized environment using Oracle VirtualBox.

The network integrates DHCP, DNS, Zimbra Mail Server, Samba Active Directory, and Apache Web Server to provide automated IP addressing, email communication, centralized user management, and web hosting.

## Technologies Used

- **Operating Systems:** Ubuntu Linux, CentOS
- **Virtualization:** Oracle VirtualBox
- **Mail Server:** Zimbra Collaboration Suite
- **Directory Services:** Samba Active Directory, Kerberos
- **Network Services:** DHCP (Kea), DNS (BIND)
- **Web Server:** Apache HTTP Server
- **Administration:** Linux CLI, SSH

## Key Features

### 1. Virtual Network Configuration
- Created multiple Ubuntu and CentOS virtual machines.
- Configured NAT, Bridged, and Host-Only network adapters.
- Established client-server connectivity within the virtual network.

### 2. DHCP and DNS Services
- Configured dynamic IP address allocation using DHCP.
- Implemented the `192.168.0.0/24` network with a DHCP address pool of `192.168.0.100–192.168.0.200`.
- Configured DNS services for hostname resolution.

### 3. Zimbra Mail Server
- Installed and configured Zimbra Collaboration Suite.
- Created and managed multiple email accounts.
- Tested mail server connectivity and accessed the Zimbra webmail interface.

### 4. Samba Active Directory
- Configured a Samba Active Directory Domain Controller.
- Created organizational units for Admins, Staff, and Students.
- Managed domain users and configured Kerberos authentication.

### 5. Apache Web Server
- Installed and configured Apache HTTP Server.
- Hosted a custom HTML webpage displaying "HELLO NMA".
- Verified webpage accessibility from a client machine.

## Testing and Verification

The project included testing of:

- Virtual machine network connectivity
- DHCP address allocation
- DNS hostname resolution
- Zimbra mail services and webmail access
- Samba Active Directory service and user management
- Apache web server availability and client-side access

## Skills Demonstrated

Linux System Administration | Network Configuration | Server Deployment | Virtualization | DHCP & DNS | Email Server Administration | Active Directory | Troubleshooting | Network Service Verification

## Project Documentation

The repository contains the implementation report, configuration evidence, and screenshots demonstrating the deployed network services.

## Project Type

Individual Academic Assignment – Network Management and Administration (IE2110), Sri Lanka Institute of Information Technology (SLIIT).
