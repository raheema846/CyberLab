# TCP vs UDP

## Definition

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are Transport Layer (Layer 4) protocols used for communication between devices.

## TCP

Features:
- Connection-oriented
- Reliable
- Ordered delivery
- Error checking
- Retransmission

Examples:
- HTTP
- HTTPS
- SSH
- FTP
- SMTP

## UDP

Features:
- Connectionless
- Faster
- Low overhead
- No retransmission
- No guaranteed delivery

Examples:
- DNS
- DHCP
- Online Gaming
- VoIP
- Video Streaming

## TCP vs UDP

| TCP | UDP |
|------|-----|
| Reliable | Faster |
| Connection-oriented | Connectionless |
| Ordered delivery | No ordering guarantee |
| Higher overhead | Lower overhead |

## TCP Three-Way Handshake

1. SYN
2. SYN-ACK
3. ACK

Connection established.

## Common Ports

| Port | Service | Protocol |
|------|----------|----------|
| 20/21 | FTP | TCP |
| 22 | SSH | TCP |
| 23 | Telnet | TCP |
| 25 | SMTP | TCP |
| 53 | DNS | UDP (primarily) |
| 67/68 | DHCP | UDP |
| 80 | HTTP | TCP |
| 443 | HTTPS | TCP |

## Useful Commands

```bash
ss -tuln
ss -tun
ss -tln | grep 22
```

## My Practice

SSH:
- Port 22 was listening.

Active HTTPS connections:
- Port 443

DHCP:
- UDP ports 67 and 68

## Cybersecurity Relevance

- TCP SYN Flood attacks target TCP.
- DNS amplification attacks target UDP.
- Port scanning tools like Nmap identify open TCP and UDP ports.

## Summary

- TCP is reliable.
- UDP is faster.
- Both work at the Transport Layer.
- Understanding TCP and UDP is essential for networking and cybersecurity.
