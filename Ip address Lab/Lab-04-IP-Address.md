# Lab 04: IP Address & Static IP Configuration

## Objective
Learn IP Address basics and configure Static IP on Windows.

## Commands Used

| Command | Purpose |
|---------|---------|
| `ipconfig` | IP, Subnet, Gateway |
| `ipconfig /all` | IP, DNS, MAC |
| `ping 8.8.8.8` | Internet test |
| `ping google.com` | DNS test |
| `nslookup google.com` | DNS check |
| `ncpa.cpl` | Adapter settings |

## Private IP Ranges

| Type | Range |
|------|-------|
| Class A | 10.0.0.0 – 10.255.255.255 |
| Class B | 172.16.0.0 – 172.31.255.255 |
| Class C | 192.168.0.0 – 192.168.255.255 |
| APIPA | 169.254.0.0 – 169.254.255.255 |
| Loopback | 127.0.0.1 |

## Static IP Settings Used

| Field | Value |
|-------|-------|
| IP Address | 192.168.1.100 |
| Subnet Mask | 255.255.255.0 |
| Gateway | 192.168.1.1 |
| DNS | 8.8.8.8 |

## Steps

1. Ran `ipconfig` and `ipconfig /all`
2. Tested with `ping 8.8.8.8`, `ping google.com`, `nslookup google.com`
3. Opened `ncpa.cpl` → Adapter Properties → IPv4
4. Set Static IP
5. Verified with `ipconfig` and `ping`
6. Reverted to DHCP

## What I Learned
- IP Address fundamentals
- Private IP ranges
- Static IP vs DHCP
- ipconfig, ping, nslookup
- DNS and MAC Address

## Screenshots

Screenshots are in the `screenshots/` folder.