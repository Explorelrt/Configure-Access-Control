# Implementing AAA Authentication and Network Services

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
<img alt="01-network-topology" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/topology/01-network-topology.png" />
<img alt="02-network-topology-ISP" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/topology/02-network-topology-ISP.png" />
<img alt="03-network-topology-HQ" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/topology/03-network-topology-HQ.png" />

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
<img alt="04-AAA-server" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/04-AAA-server.png" />

- Configure wireless authentication on HQ-Laptop-1.
<img alt="05-authenticate-HQ-Laptop-1" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/05-authenticate-HQ-Laptop-1.png" />

- Configure wireless authentication on HQ-Laptop-2.
<img alt="06-authenticate-HQ-Laptop-2" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/06-authenticate-HQ-Laptop-2.png" />

### Configure and Use Email Services
- Activate email services and configure email user accounts.
<img alt="07-email-services" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/07-email-services.png" />

- Configure email clients.
<img alt="08-email-clients" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/08-configure-email-clients.png" />

- Send an email as So-Ia.
<img alt="09-email-sent" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/09-email-sent.png" />
<img alt="10-email-received" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/10-email-received.png" />

### Configure and Use FTP Services
- Activate the FTP service.
<img alt="11-FTP-service" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/11-FTP-service.png" />

- Create the FTP user accounts.
<img alt="12-FTP-user-add" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/12-FTP-user-add.png" />

- Transfer files between Net-Admin and the FTP server. Use the get command to download aMessage.txt.
<img alt="13-FTP-login" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/13-FTP-login.png" />

- Open the downloaded file aMessage.txt.
<img alt="14-FTP-file" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/14-FTP-file.png" />

- Log back in to the FTP server as user soia.
Use the put command to upload aMessage_new.txt.
<img alt="15-FTP-file-upload" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/15-FTP-file-upload.png" />

- Verify FTP user privileges are working as configured. Login to the FTP server at 192.168.75.2 with username mia and password cisco123.
<img alt="16-FTP-user-privileges" src="https://raw.githubusercontent.com/Explorelrt/Configure-Access-Control/main/screenshots/16-FTP-user-privileges.png" />

## Key Learnings
- Understanding AAA authentication and access control.
- Configuring network services in Cisco Packet Tracer.
- Understanding SMTP, POP3, and FTP protocols.
- Testing and troubleshooting network services.
- Improving practical networking and infrastructure skills.
  
