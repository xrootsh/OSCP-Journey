Common Network Ports

What is a Port?

A port is a communication endpoint used by applications and services.

Purpose:
Allows multiple services to run on the same device.

Example:

IP Address: 192.168.1.10
Port: 80

A service listens on a specific port.

---

Port 20/21 - FTP

Service:
FTP (File Transfer Protocol)

Purpose:
Transfers files between systems.

Example:

ftp://example.com

Default Ports:

20 - Data Transfer
21 - Control Connection

---

Port 22 - SSH

Service:
Secure Shell (SSH)

Purpose:
Secure remote access to Linux systems.

Example:

ssh user@192.168.1.10

Real World Use:
Remote server administration.

---

Port 23 - Telnet

Service:
Telnet

Purpose:
Remote command-line access.

Note:
Not encrypted.

Real World Use:
Mostly replaced by SSH.

---

Port 25 - SMTP

Service:
Simple Mail Transfer Protocol

Purpose:
Sends email between mail servers.

Real World Use:
Email delivery.

---

Port 53 - DNS

Service:
Domain Name System

Purpose:
Converts domain names into IP addresses.

Example:

google.com → IP address

---

Port 67/68 - DHCP

Service:
Dynamic Host Configuration Protocol

Purpose:
Automatically assigns IP addresses.

Real World Use:
Home routers and enterprise networks.

---

Port 80 - HTTP

Service:
HyperText Transfer Protocol

Purpose:
Delivers web pages.

Example:

http://example.com

---

Port 110 - POP3

Service:
Post Office Protocol Version 3

Purpose:
Receives email.

Real World Use:
Mail clients.

---

Port 123 - NTP

Service:
Network Time Protocol

Purpose:
Synchronizes system time.

Real World Use:
Servers and network devices.

---

Port 139 - NetBIOS

Service:
NetBIOS

Purpose:
Windows network communication.

Real World Use:
Legacy Windows systems.

---

Port 143 - IMAP

Service:
Internet Message Access Protocol

Purpose:
Access email on a mail server.

Real World Use:
Modern email clients.

---

Port 161 - SNMP

Service:
Simple Network Management Protocol

Purpose:
Monitor network devices.

Examples:

- Routers
- Switches
- Printers

---

Port 389 - LDAP

Service:
Lightweight Directory Access Protocol

Purpose:
Directory services and authentication.

Real World Use:
Enterprise environments.

---

Port 443 - HTTPS

Service:
HyperText Transfer Protocol Secure

Purpose:
Encrypted web communication.

Example:

https://example.com

---

Port 445 - SMB

Service:
Server Message Block

Purpose:
File and printer sharing.

Real World Use:
Windows file sharing.

---

Port 3306 - MySQL

Service:
MySQL Database

Purpose:
Database communication.

Real World Use:
Web applications.

---

Port 3389 - RDP

Service:
Remote Desktop Protocol

Purpose:
Remote Windows access.

Real World Use:
Windows administration.

---

Port 5432 - PostgreSQL

Service:
PostgreSQL Database

Purpose:
Database communication.

Real World Use:
Enterprise applications.

---

Quick Summary

20/21 - FTP

22 - SSH

23 - Telnet

25 - SMTP

53 - DNS

67/68 - DHCP

80 - HTTP

110 - POP3

123 - NTP

139 - NetBIOS

143 - IMAP

161 - SNMP

389 - LDAP

443 - HTTPS

445 - SMB

3306 - MySQL

3389 - RDP

5432 - PostgreSQL

---

Easy Memory Trick

Web:
80 HTTP
443 HTTPS

Remote Access:
22 SSH
3389 RDP

File Sharing:
21 FTP
445 SMB

Email:
25 SMTP
110 POP3
143 IMAP

Infrastructure:
53 DNS
67/68 DHCP
123 NTP
