# Service Analysis

## Finding

During internal network reconnaissance, the target Ubuntu Server was identified as running an SSH service.

## Discovered Service

Service:
- SSH (Secure Shell)

Port:
- 22/tcp

Purpose:
SSH provides remote administration access to Linux systems.

## Risk Analysis

Risk Level:
Medium

Reason:

SSH itself is a legitimate administration service, but improper configuration can create security risks.

Possible risks:
- Weak passwords
- Unauthorized access attempts
- Poor access control
- Outdated SSH versions

## Security Recommendations

- Use strong authentication
- Disable unnecessary access
- Monitor login attempts
- Keep SSH packages updated
- Restrict administrative access

## Analyst Notes

The service was identified using Nmap service detection:

```bash
sudo nmap -sS -sV 192.168.56.101
```

This demonstrates internal asset discovery and service enumeration in a controlled SOC lab environment.
