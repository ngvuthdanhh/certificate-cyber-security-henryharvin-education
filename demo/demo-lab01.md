# Demo Lab 01 – Network Scanning with Nmap

## Objective
Perform network discovery and identify open ports on a target VM.

## Steps
1. Launch Kali Linux  
2. Run basic scan:  
   ```bash
   nmap 192.168.1.10
   ```
3. Perform service version detection:

 ```bash
nmap -sV 192.168.1.10
  ```
4. Save results to file:
 ```bash

nmap -oN scan-results.txt 192.168.1.10
 ```
## Expected Outcome

- List of open ports and running services

- Identification of potential vulnerabilities
