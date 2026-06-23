# SOC Reconnaissance Report

## Project Overview

This project demonstrates a basic SOC analyst workflow by creating an isolated virtual lab environment and performing internal network reconnaissance.

The objective was to identify active hosts, discover exposed services, and analyze security implications.

---

# Lab Environment

## Analyst Machine

Role:
Security analysis and reconnaissance

IP Address:
192.168.56.102

Tools Used:
- Nmap


## Target Machine

Role:
Simulated internal server asset

Operating System:
Ubuntu Server

IP Address:
192.168.56.101

---

# Network Configuration

Network Type:

Host-only Adapter

Purpose:

A controlled isolated network was created between the Analyst VM and Target VM for security testing and learning.

---

# Reconnaissance Activity

## Tool Used

Nmap

Command:

```bash
sudo nmap -sS -sV 192.168.56.101
```

---

# Findings

## Finding 1: SSH Service Exposed

Service:
SSH

Port:
22/tcp

Status:
Open


Description:

The target machine allows SSH connections, providing remote administration capability.

---

# Risk Assessment

Severity:
Medium


Reason:

SSH is commonly used for administration, but insecure configurations may allow unauthorized access attempts.

---

# Recommendations

- Use strong passwords
- Monitor authentication logs
- Restrict unnecessary access
- Keep services updated
- Review exposed services regularly

---

# Conclusion

The lab successfully demonstrated:

- Virtual SOC environment setup
- Network configuration
- Host discovery
- Service enumeration
- Basic security analysis

This project represents the initial phase of building a practical SOC analyst home lab.
