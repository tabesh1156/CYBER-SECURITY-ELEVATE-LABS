# CYBER-SECURITY-ELEVATE-LABS
# Task 1: Local Network Port Scanning

## Objective
To identify open ports and services running on devices in my local network using Nmap.

## Network Range
192.168.1.0/24

## Results
Two active devices were discovered.

### Device 1: 192.168.1.1 (Router - TP-Link)
Open Ports:
- 22/tcp (SSH)
- 53/tcp (DNS)
- 80/tcp (HTTP)
- 1900/tcp (UPnP)
- 2000/tcp

### Device 2: 192.168.1.108 (Local Machine)
Open Ports:
- 135/tcp (MSRPC)
- 139/tcp (NetBIOS)
- 445/tcp (Microsoft-DS)

## Security Analysis
- SSH may allow brute-force attacks if weak passwords are used.
- HTTP port exposes router admin panel.
- SMB (445) can be exploited if not properly secured.
- NetBIOS and RPC services may expose internal file sharing services.

## Conclusion
This task helped me understand network reconnaissance, port scanning, and how exposed services may pose security risks.
