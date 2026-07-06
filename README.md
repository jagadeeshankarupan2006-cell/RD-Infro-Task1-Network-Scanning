# RD-Infro-Task1-Network-Scanning
Cyber Security Internship 
Task 1 - Network Scanning and Reconnaissance using Nmap

## Student Details

Name:Jagadeeshan A
USN:24BTLCC002
University:Jain University Faculty of Engineering and Technology
Department:Computer Science Engineering (Cyber Security)


## Objective

The objective of this task is to perform network reconnaissance on a target system using Nmap. The scan identifies active hosts, open ports, running services, and operating system information.


## Tool Used

-Nmap 7.99
-Windows 11

## Command Used

```bash
nmap -sV -A 10.171.65.231
```

## Scan Results

| Port | State | Service | Version |
|------|-------|---------|---------|
| 135 | Open | msrpc | Microsoft Windows RPC |
| 139 | Open | netbios-ssn | Microsoft Windows NetBIOS |
| 445 | Open | microsoft-ds | SMB File Sharing |
| 3306 | Open | mysql | MySQL (Unauthorized) |


## Operating System

Microsoft Windows 11 (24H2–25H2)

## Findings

- Target host was online.
- Four TCP ports were open.
- Microsoft RPC, NetBIOS, SMB, and MySQL services were detected.
- Operating system was successfully identified as Windows 11.


## Conclusion

This task demonstrated how Nmap can be used for network reconnaissance by identifying open ports, services, and operating system information. The scan provides valuable information for security assessment and network management.

## Screenshots

Screenshots are available in the `screenshots` folder.

