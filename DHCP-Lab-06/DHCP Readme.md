# Lab 06: DHCP

## Objective
Learn DHCP basics and test IP release and renew.

## Commands Used

| Command | Purpose |
|---------|---------|
| `ipconfig /all` | View DHCP info |
| `ipconfig /release` | Release IP |
| `ipconfig /renew` | Get new IP |
| `ipconfig` | View IP |

## DORA Process

| Step | Action |
|------|--------|
| 1 | Discover |
| 2 | Offer |
| 3 | Request |
| 4 | Ack |

## Lease Info

| Field | Value |
|-------|-------|
| Lease Time | 24 hours |
| Renewal (T1) | 50% (12h) |
| Rebinding (T2) | 87.5% (21h) |

## APIPA

- Range: 169.254.x.x
- Meaning: DHCP not found
- Solution: ipconfig /renew

## Steps

1. Ran `ipconfig /all` - saw DHCP info
2. Ran `ipconfig /release` - released IP
3. Ran `ipconfig /renew` - got new IP
4. Verified with `ping`

## Results

- IP released and renewed successfully
- New IP received from DHCP
- Internet working

## What I Learned
- DHCP = Auto IP
- DORA process
- DHCP Lease
- APIPA = 169.254.x.x
- release and renew

## Screenshots
Screenshots are in the `screenshots/` folder.