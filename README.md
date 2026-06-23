# SOC Lab: Network Reconnaissance & Service Enumeration

## Overview

This project documents the creation of a practical SOC home lab environment using VirtualBox and Ubuntu systems.

The lab simulates an internal enterprise environment where a security analyst performs asset discovery, service enumeration, and basic risk assessment.

---

# Lab Architecture

## Analyst VM

Role:
Security Analyst Workstation

IP:
192.168.56.102

Tools:
- Nmap


## Target VM

Role:
Simulated Linux Server Asset

OS:
Ubuntu Server

IP:
192.168.56.101


Network:
Host-only isolated network

---

# Objectives

- Build an isolated cybersecurity lab
- Perform internal network reconnaissance
- Identify exposed services
- Analyze security risks
- Document findings like a SOC analyst

---

# Tools Used

- VirtualBox
- Ubuntu Linux
- Ubuntu Server
- Nmap
- SSH

---

# Project Workflow

1. Created virtual lab environment
2. Configured isolated networking
3. Enabled SSH service on target machine
4. Performed Nmap reconnaissance
5. Analyzed discovered services
6. Created SOC-style report

---

# Key Finding

## SSH Service Exposure

Port:
22/tcp

Service:
SSH

Risk:
Medium

Reason:

SSH provides remote administration capability and requires proper security controls.

---

# Skills Demonstrated

- Linux administration
- Virtual networking
- Service enumeration
- Nmap usage
- Basic vulnerability assessment
- Technical documentation

---

# Future Improvements

Planned additions:

- Log monitoring
- SIEM integration
- Vulnerability scanning
- Attack simulation
- Detection engineering
