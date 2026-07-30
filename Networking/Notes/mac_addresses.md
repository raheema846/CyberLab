# MAC Addresses and ARP

## Definition

A MAC (Media Access Control) address is a unique physical address assigned to a network interface.

Example:
08:00:27:8a:35:d2

## Why is it Important?

- Identifies devices on a local network
- Used for communication within a LAN
- Works together with IP addresses

## IP Address vs MAC Address

| IP Address | MAC Address |
|------------|-------------|
| Logical address | Physical address |
| Can change | Usually remains the same |
| Used between networks | Used within a local network |

## What is ARP?

ARP (Address Resolution Protocol) converts an IP address into a MAC address so devices can communicate on a local network.

Example:

IP: 10.0.2.2

↓

MAC: 52:55:0a:00:02:02

## Useful Commands

```bash
ip a
ip neigh
ping -c 4 10.0.2.2
```

## My Practice

My MAC Address:
- 08:00:27:8a:35:d2

My Interface:
- eth0

Gateway:
- 10.0.2.2

Gateway MAC:
- 52:55:0a:00:02:02

## Cybersecurity Relevance

Attackers may use ARP Spoofing to redirect traffic through their own device and perform Man-in-the-Middle attacks.

## Summary

- Every network interface has a MAC address.
- ARP maps IP addresses to MAC addresses.
- MAC addresses are used for communication on the local network.
- Understanding ARP is essential before learning ARP spoofing and network attacks.
