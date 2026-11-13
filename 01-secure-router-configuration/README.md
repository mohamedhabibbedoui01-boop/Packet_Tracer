# Project 01 — Secure Router Configuration

## Overview

This project focuses on configuring and securing a Cisco router using Cisco Packet Tracer.

## Objectives

- Configure basic router settings.
- Set passwords for privileged EXEC access.
- Configure console and VTY line access.
- Encrypt plaintext passwords.
- Configure SSH for secure remote administration.
- Disable insecure Telnet access.

## Tools & Technologies

- Cisco Packet Tracer
- Cisco IOS CLI
- Router configuration
- SSH
- Network security fundamentals

## Network Topology

Add a screenshot of your Packet Tracer topology here.

## Configuration

The main configuration tasks include:

1. Set the router hostname.
2. Configure the enable secret.
3. Secure console access.
4. Create a local administrative user.
5. Configure an IP domain name.
6. Generate RSA keys.
7. Enable SSH version 2.
8. Restrict remote access to SSH.

## Verification

Commands used for verification:
```
show running-config
show ip interface brief
show ip ssh
show users
```

Test SSH access from a connected PC.

## Project Files

- `project.pkt` — Packet Tracer simulation.
- `configs/` — Router configuration files.
- `screenshots/` — Network topology and verification evidence.

## Learning Outcomes

- Understanding basic Cisco IOS configuration.
- Applying secure router management practices.
- Understanding SSH-based remote administration.
- Verifying router security configurations.

## Project Status

**Status:** In Progress

More configuration details and test results will be added as the project develops.

---

Created as part of my Cisco Networking and Cybersecurity learning journey.
