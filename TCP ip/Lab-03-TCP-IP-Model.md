# Lab 03: TCP/IP Model & 3-Way Handshake

## Objective
Explore TCP/IP 4 layers and capture TCP 3-way handshake using Wireshark.

## Tools Used
- Wireshark
- Windows Command Line

## Results

### TCP 3-Way Handshake Found

| Packet | Source | Destination | Flags |
|--------|--------|-------------|-------|
| 902 | 192.168.10.18 | 52.110.14.176 | SYN |
| 903 | 52.110.14.176 | 192.168.10.18 | SYN, ACK |
| 904 | 192.168.10.18 | 52.110.14.176 | ACK |

### Details
- MAC Address: Intel_b2:04:2b
- IP Address: 192.168.10.18
- Port: 443 (HTTPS)
- TLS Handshake: Client Hello (mrodevicemgr.officeapps.live.com)

## What I Learned
- TCP/IP 4 layers in real-world
- TCP 3-way handshake (SYN, SYN-ACK, ACK)
- Wireshark filters
- Follow TCP Stream
- MAC, IP, Port analysis

## Screenshots

Screenshots are in the `screenshots/` folder.