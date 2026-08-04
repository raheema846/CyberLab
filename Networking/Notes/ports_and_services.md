# Ports and Network Services

## What is a Port?

A port is a logical communication endpoint used by applications on a computer.

An IP address identifies the device.

A port identifies the application running on that device.

Example:

IP Address -> 10.0.2.15
Port -> 22 (SSH)

---

## Common Ports

20/21 - FTP

22 - SSH

23 - Telnet

25 - SMTP

53 - DNS

67/68 - DHCP

80 - HTTP

110 - POP3

143 - IMAP

443 - HTTPS

3306 - MySQL

3389 - Remote Desktop (RDP)

---

## Commands Learned

Show listening ports

```bash
ss -tuln
```

Show listening ports with process name

```bash
sudo ss -tulpn
```

Scan localhost

```bash
sudo nmap localhost
```

Detect service versions

```bash
sudo nmap -sV localhost
```

---

## Practical Observation

Listening port:

22/tcp

Service:

SSH

Program:

sshd

Version:

OpenSSH 10.3p1 Debian 5

---

## Important

Attackers scan ports to discover running services.

Defenders scan ports to ensure unnecessary services are not exposed.

Keeping unused ports closed improves security.

