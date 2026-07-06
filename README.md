# RD INFRO TECHNOLOGY - Cyber Security Internship

## Task 1: Network Scanning and Reconnaissance using Nmap

## Student Details

- Name:Jagadeeshan A
- USN: 24BTLCC002
- University: Jain University
- Faculty: Faculty of Engineering and Technology
- Department: Computer Science Engineering (Cyber Security)


## Project Overview

This project demonstrates the use of **Nmap (Network Mapper)** to perform network scanning and reconnaissance on a local system. The scan identifies active hosts, open ports, running services, and operating system information. This task helps understand the first phase of penetration testing and network security assessment.


## Objective

- Perform network reconnaissance.
- Identify open TCP ports.
- Detect running services.
- Identify the operating system.
- Analyze the scan results.


## Tool Used

- Nmap 7.99
- Windows 11


## Command Used

```bash
nmap -sV -A 10.171.65.231
```


## Scan Results

| Port | State | Service | Description |
|------|-------|----------|-------------|
| 135 | Open | MSRPC | Microsoft Remote Procedure Call |
| 139 | Open | NetBIOS | File and Printer Sharing |
| 445 | Open | Microsoft-DS | SMB Service |
| 3306 | Open | MySQL | MySQL Database Service |


## Operating System

Microsoft Windows 11 (24H2–25H2)


## Repository Structure

```
RD-Infro-Task1-Network-Scanning
│
├── README.md
├── screenshots
│   ├── Screenshot of ipconfig.png
│   └── Screenshot of nmap.png
└── output
    └── nmap_scan.txt
```


## Screenshots

### IP Configuration
![IP Configuration](screenshots/Screenshot%20of%20ipconfig.png)

### Nmap Scan Output

![Nmap Scan Output](screenshots/Screenshot%20of%20nmap.png)


## Output File

The complete scan output is available in:

- `output/nmap_scan.txt`


## Conclusion

The network scan was successfully completed using Nmap. The scan identified active services, open ports, and the operating system of the target machine. This practical task provided hands-on experience with network reconnaissance and basic security assessment techniques.


## Internship

**Organization:** RD INFRO TECHNOLOGY

**Internship Domain:** Cyber Security

**Task Completed:** Task 1 – Network Scanning and Reconnaissance
