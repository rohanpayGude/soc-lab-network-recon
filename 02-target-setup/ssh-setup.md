# SSH Service Setup

## Overview

SSH (Secure Shell) was enabled on the Ubuntu Server target machine to simulate a remotely accessible service.

## Installation

OpenSSH server was installed using:

```bash
sudo apt install openssh-server -y
```

## Service Verification

The SSH service was checked using:

```bash
systemctl status ssh
```

Result:

- SSH service active and running

## Network Exposure

SSH runs on:

Port:
- 22/tcp

This service was later identified through Nmap scanning from the Analyst VM.

## Security Consideration

SSH provides remote administration access.

Security factors to monitor:
- Strong authentication
- Password security
- Access restrictions
- Exposure level
