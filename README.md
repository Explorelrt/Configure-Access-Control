# Implementing AAA Authentication for Network Services

## Project Overview
This project demonstrates the configuration and implementation of AAA authentication for network services using Cisco Packet Tracer. 
The lab focuses on implementing AAA (Authentication, Authorization, and Accounting) for network services including wireless network services, email, and file transfer services to understand how network devices and servers manage secure access and communication.

## Objectives
- Configure and implement AAA authentication credentials.
- Configure and test email services.
- Configure and test FTP services.

## Tools and Technologies
- Cisco Packet Tracer
- Cisco Networking Devices (Routers and Switches)
- AAA Authentication
- Email Services (SMTP/POP3)
- FTP Services
- TCP/IP Networking

## Network Topology
<img alt="01-network-topology" src="./topology/01-network-topology.png"></img>
<img alt="02-network-topology-ISP" src="./topology/02-network-topology-ISP.png"></img>
<img alt="03-network-topology-HQ" src="./topology/03-network-topology-HQ.png"></img>

## Email User Accounts
| PC/Laptop | Name | Email Address | Username | Password |
|-----------|------|---------------|-----------|----------|
| 1-1 | Soia | HQuser1@mail.cyberhq.com | HQuser1 | Cisco123! |
| Net-Admin | Cisco | HQuser2@mail.cyberhq.com | HQuser2 | Cisco123~ |
| 2-1 | Ava | BRuser1@mail.cyberhq.com | BRuser1 | Cisco123- |
| HQ-Laptop-1 | Mia | BRuser2@mail.cyberhq.com | BRuser2 | Cisco123+ |

## FTP User Accounts
| Username | Password | User Privilege |
|----------|----------|----------------|
| soia | cisco123 | RWDNL (Read, Write, Delete, Rename, List) |
| ava | cisco321 | RWDNL (Read, Write, Delete, Rename, List) |
| mia | cisco123 | RWNL (Read, Write, Rename, List) |
## Project Implementation

### Configure and Use AAA Authentication Credentials
- Configure user accounts on the AAA-RADIUS server.
<img alt="04-AAA-server" src="./screenshots/04-AAA-server.png"></img>

- Configure wireless authentication on HQ-Laptop-1.
<img alt="05-authenticate-HQ-Laptop-1" src="./screenshots/05-authenticate-HQ-Laptop-1.png"></img>

- Configure wireless authentication on HQ-Laptop-2.
<img alt="06-authenticate-HQ-Laptop-2" src="./screenshots/06-authenticate-HQ-Laptop-2.png"></img>

### Configure and Use Email Services
- Activate email services and configure email user accounts.
<img alt="07-email-services" src="./screenshots/07-email-services.png"></img>

- Configure email clients.
<img alt="08-email-clients" src="./screenshots/08-configure-email-clients.png"></img>

- Send an email as So-Ia.
<img alt="09-email-sent" src="./screenshots/09-email-sent.png"></img>
<img alt="10-email-received" src="./screenshots/10-email-received.png"></img>

### Configure and Use FTP Services
- Activate the FTP service.
<img alt="11-FTP-service" src="./screenshots/11-FTP-service.png"></img>

- Create the FTP user accounts.
<img alt="12-FTP-user-add" src="./screenshots/12-FTP-user-add.png"></img>

- Transfer files between Net-Admin and the FTP server. Use the get command to download aMessage.txt.
<img alt="13-FTP-login" src="./screenshots/13-FTP-login.png"></img>

- Open the downloaded file aMessage.txt.
<img alt="14-FTP-file" src="./screenshots/14-FTP-file.png"></img>

- Log back in to the FTP server as user soia.
Use the put command to upload aMessage_new.txt.
<img alt="15-FTP-file-upload" src="./screenshots/15-FTP-file-upload.png"></img>

- Verify FTP user privileges are working as configured. Login to the FTP server at 192.168.75.2 with username mia and password cisco123.
<img alt="16-FTP-user-privileges" src="./screenshots/16-FTP-user-privileges.png"></img>

## Key Learnings
- Understanding AAA authentication and access control.
- Configuring network services in Cisco Packet Tracer.
- Understanding SMTP, POP3, and FTP protocols.
- Testing and troubleshooting network services.
- Improving practical networking and infrastructure skills.
  
