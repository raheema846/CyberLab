# Domain Name System (DNS)

## What is DNS?

DNS (Domain Name System) translates domain names into IP addresses.

Example:

google.com → 142.251.222.142

Computers communicate using IP addresses, while humans remember domain names.

---

## DNS Uses

- Website access
- Email routing
- Name resolution

---

## DNS Port

Port: 53

Protocols:

- UDP (most queries)
- TCP (large responses and zone transfers)

---

## Common DNS Records

A - IPv4 Address

AAAA - IPv6 Address

MX - Mail Server

NS - Name Server

CNAME - Alias

TXT - Text Record

---

## Commands Learned

### host

```bash
host google.com
```

### nslookup

```bash
nslookup google.com
```

### dig

```bash
dig google.com
```

---

## Practical Observation

DNS Server:

192.168.31.1

Google IPv4:

142.251.222.142

GitHub IPv4:

20.207.73.82

Google IPv6:

2404:6800:4007:832::200e

---

## Cybersecurity Relevance

DNS is used during reconnaissance to identify servers, mail systems, and infrastructure.

Security analysts monitor DNS traffic to detect phishing, malware, and suspicious communications.

---

## Summary

- DNS converts domain names into IP addresses.
- DNS mainly uses UDP Port 53.
- The `dig` command provides the most detailed DNS information.
