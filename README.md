# Nmap-network-scanning-analysis
Beginner cybersecurity project demonstrating network scanning and service enumeration using Nmap.
# Nmap Network Scanning and Service Enumeration

## Project Overview
This project demonstrates basic network reconnaissance using Nmap.

The goal was to identify open ports, running services, and operating system details of a target system.

## Tool Used
- Nmap

## Scans Performed

### 1. Basic Scan

Command used:
nmap scanme.nmap.org

Purpose:
Identify open ports and running services.

### 2. Advanced Scan
Command used:
nmap -A scanme.nmap.org

Purpose:
Perform service detection, OS detection, and traceroute.

## Key Findings
- Open ports detected: 22 (SSH), 53 (DNS), 80 (HTTP)
- Web server detected: Apache
- OS likely Linux

## Learning Outcome

## Windows Event Log Analysis - Detecting Failed Login Attempts

The screenshot below shows multiple failed login attempts (Event ID 4625) detected in Windows Security logs.

![Failed Login Detection](failed-login-detection.png)
This project helped me understand how cybersecurity professionals perform network reconnaissance and identify exposed services in a network.
