# Nmap Vulnerability Assessment – Shashank Budhlakoti

## Objective
To identify open ports, active services, OS fingerprint, and security vulnerabilities using advanced Nmap scanning techniques.

## Tools Used
- Nmap  
- Linux Terminal  
- WHOIS  
- Netcat  
- NSE Scripts  

## Methodology

### 1. Host Discovery
`nmap -sn <target-ip>`

### 2. Port & Service Enumeration
`nmap -sV <target-ip>`

### 3. OS Fingerprinting
`nmap -A <target-ip>`

### 4. Vulnerability Detection
`nmap --script vuln <target-ip>`

## Findings
- Open ports detected  
- Outdated services  
- Potential vulnerabilities  

## Outcome
Learned practical vulnerability scanning workflow used in real VAPT assessments.
