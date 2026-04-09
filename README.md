# Task 1: Scan Your Local Network for Open Ports

## Objective
To discover open ports on devices in the local network using Nmap and understand network exposure.

## Tools Used
- Nmap
- Command Prompt (Windows)

## Steps Performed
1. Installed Nmap on Windows system
2. Found local IP address using ipconfig
3. Identified IP range (10.83.127.0/24)
4. Performed TCP SYN scan using Nmap
5. Identified active hosts and open ports
6. Saved scan results to text file

## Command Used
nmap -sS 10.83.127.0/24

## Results
Two hosts were discovered in the local network:
- 10.83.127.217 (DNS port 53 open)
- 10.83.127.140 (Ports 135, 139, 445, 3580, 8090 open)

## Security Risks Identified
- File sharing ports exposed (139, 445)
- Remote procedure call service running (135)
- Multiple open ports increase attack surface

## Outcome
Learned how to scan a local network, identify open ports, and understand potential security risks.
