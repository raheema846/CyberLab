# OSI Model

## Definition

The OSI (Open Systems Interconnection) Model is a conceptual framework that explains how data travels across a network using seven layers.

## The Seven Layers

| Layer | Name | Function |
|------:|------|----------|
| 7 | Application | User interaction and network services |
| 6 | Presentation | Encryption, compression, formatting |
| 5 | Session | Establishes and manages communication sessions |
| 4 | Transport | Reliable data delivery using TCP/UDP |
| 3 | Network | Routing using IP addresses |
| 2 | Data Link | Communication using MAC addresses |
| 1 | Physical | Cables, signals, and hardware |

## Memory Trick

Application

Presentation

Session

Transport

Network

Data Link

Physical

Mnemonic:

**All People Seem To Need Data Processing**

## Layer Functions

### Layer 7 – Application
Protocols:
- HTTP
- HTTPS
- FTP
- SMTP
- DNS

### Layer 6 – Presentation
- Encryption
- Compression
- Data formatting

### Layer 5 – Session
- Starts
- Maintains
- Ends communication sessions

### Layer 4 – Transport
Protocols:
- TCP
- UDP

### Layer 3 – Network
Uses:
- IP addresses
- Routers

### Layer 2 – Data Link
Uses:
- MAC addresses
- Switches
- ARP

### Layer 1 – Physical
Examples:
- Ethernet cable
- Fiber optic cable
- Wi-Fi signals

## Cybersecurity Relevance

- Layer 7: SQL Injection, XSS
- Layer 6: Weak encryption
- Layer 5: Session Hijacking
- Layer 4: SYN Flood attacks
- Layer 3: IP Spoofing
- Layer 2: ARP Spoofing
- Layer 1: Physical cable attacks

## Useful Commands

```bash
ip a
ip neigh
ping 8.8.8.8
```

## My Practice

- IP addresses are used at Layer 3 (Network).
- MAC addresses are used at Layer 2 (Data Link).
- TCP and UDP work at Layer 4 (Transport).

## Summary

- The OSI model has seven layers.
- Each layer has a specific responsibility.
- Understanding the OSI model helps troubleshoot networks and analyze cyberattacks.
