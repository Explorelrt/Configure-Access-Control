# Implementing AAA Authentication for Network Services

## Overview
This project demonstrates the configuration and implementation of AAA authentication for network services using Cisco Packet Tracer. 
The lab focuses on implementing AAA (Authentication, Authorization, and Accounting) for network services including wireless network services, email, and file transfer services to understand how network devices and servers manage secure access and communication.

## Objectives
- Configure and implement AAA authentication credentials.
- Configure and test email services.
- Configure and test FTP services.
---

## Tools and Technologies
- Cisco Packet Tracer
- Cisco Networking Devices (Routers and Switches)
- AAA Authentication
- Email Services (SMTP/POP3)
- FTP Services
- TCP/IP Networking

## Network Topology
!Network Topology

## Email User Accounts
| PC/Laptop | Name | Email Address | Username | Password |
|-----------|------|---------------|-----------|----------|
| 1-1 | Suk-Yi | HQuser1@mail.cyberhq.com | HQuser1 | Cisco123! |
| Net-Admin | Cisco | HQuser2@mail.cyberhq.com | HQuser2 | Cisco123~ |
| 2-3 | Ajulo | BRuser1@mail.cyberhq.com | BRuser1 | Cisco123- |
| HQ-Laptop-1 | Malia | BRuser2@mail.cyberhq.com | BRuser2 | Cisco123+ |

## FTP User Accounts
| Username | Password | User Privilege |
|----------|----------|----------------|
| sukyi | cisco123 | RWDNL (Read, Write, Delete, Rename, List) |
| ajulo | cisco321 | RWDNL (Read, Write, Delete, Rename, List) |
| malia | cisco123 | RWNL (Read, Write, Rename, List) |
## Project Implementation

### Configure and Use AAA Authentication Credentials
- Configure user accounts on the AAA server.
- Configure wireless authentication on HQ-Laptop-1.
- Configure wireless authentication on HQ-Laptop-2.

### Configure and Use Email Services
- Activate email services and configure email user accounts.
- Configure email clients.
- Send an email as Suk-Yi.

### Configure and Use FTP Services
- Activate the FTP service.
- Create the FTP user accounts.
- Transfer files between Net-Admin and the FTP server.
- Verify FTP user privileges are working as configured.

## Key Learnings
- Understanding AAA authentication and access control.
- Configuring network services in Cisco Packet Tracer.
- Understanding SMTP, POP3, and FTP protocols.
- Testing and troubleshooting network services.
- Improving practical networking and infrastructure skills.
  
