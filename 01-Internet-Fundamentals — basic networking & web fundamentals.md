# Day 01 – How the Internet Works 🌐

## What I learned today
- History of the Web
- How the Internet works (basic packet flow)
- Types of Web: Web 1.0 / Web 2.0 / Web 3.0
- How computers communicate (layers overview)
- How data travels across the world (routing, ISPs)
- Domain Name vs IP Address
- MAC Address basics
- ISP (Internet Service Provider)
- DNS (Domain Name System)

## Key Notes / Definitions
- *Domain Name* — human-friendly name (example: example.com).
- *IP Address* — numeric address used by devices to locate each other (IPv4 / IPv6).
- *MAC Address* — hardware-level unique identifier for a network interface.
- *DNS* — translates domain names to IP addresses (global phonebook for the Internet).
- *ISP* — company that provides internet access.
- *Web 1.0* — static pages, read-only web.
- *Web 2.0* — interactive, social web.
- *Web 3.0* — decentralized / blockchain-based web.

## How data travels (short)
1. Browser requests a URL → DNS resolves domain to IP.
2. Browser opens TCP connection (or QUIC) to server IP via ISP.
3. Data packets route through multiple routers worldwide.
4. Server responds → packets return → browser renders page.

## Useful commands / quick examples

# check DNS resolution
nslookup example.com
dig example.com






## Resources 
- Lecture: Sheryians Coding School — Cohort 2.0


## Next Goal
- Study *HTTP / HTTPS* and *Client–Server model*
