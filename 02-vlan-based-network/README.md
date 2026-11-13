# Project 02 — VLAN-Based Network

## Overview

This project focuses on designing and configuring a VLAN-based network using Cisco Packet Tracer. The network is divided into separate logical groups to improve organization, manage traffic, and provide basic network segmentation.

## Objectives

- Understand the purpose of VLANs in a switched network.
- Create and name multiple VLANs.
- Assign switch ports to the correct VLANs.
- Configure end devices with appropriate IP addresses.
- Verify communication between devices in the same VLAN.
- Demonstrate isolation between different VLANs when inter-VLAN routing is not configured.

## Tools & Technologies

- Cisco Packet Tracer
- Cisco IOS CLI
- Cisco switches
- Virtual LANs (VLANs)
- IPv4 addressing
- Ethernet switching

## Network Topology

Add a screenshot of your Packet Tracer topology here.

Suggested scenario: a small organization with three departments connected to a switch:

| Department | VLAN ID | Example network |
|---|---:|---|
| Administration | 10 | 192.168.10.0/24 |
| IT | 20 | 192.168.20.0/24 |
| Guest | 30 | 192.168.30.0/24 |

These are example private lab networks. Assign each PC an unused IP address in its department's subnet.

## Configuration

The main configuration tasks include:

1. Add and connect the switch and end devices.
2. Configure the VLANs and give each VLAN a descriptive name.
3. Assign the correct switch access ports to each VLAN.
4. Configure the IP address and subnet mask on each PC.
5. Check that each switch port belongs to the intended VLAN.
6. Save the switch configuration.

Example Cisco IOS commands:

```text
enable
configure terminal

vlan 10
 name ADMIN
exit

vlan 20
 name IT
exit

vlan 30
 name GUEST
exit

interface fastEthernet 0/1
 switchport mode access
 switchport access vlan 10
exit

end
show vlan brief
```

Repeat the access-port configuration for the ports and VLANs used in your topology. Adjust interface names to match your switch model.

## Verification

Commands used for verification:

```text
show vlan brief
show running-config
show interfaces status
```

Connectivity tests:

- Ping between PCs assigned to the same VLAN.
- Confirm that PCs in different VLANs cannot communicate without a Layer 3 routing configuration.
- Check that every PC is connected to the intended switch port.

## Project Files

- `project.pkt` — Packet Tracer simulation.
- `configs/` — Switch configuration files.
- `screenshots/` — Network topology and verification evidence.
- `tests.md` — Connectivity test results and observations.

## Learning Outcomes

- Understanding Layer 2 network segmentation.
- Creating and managing VLANs on a Cisco switch.
- Assigning access ports to VLANs.
- Understanding broadcast-domain separation.
- Verifying VLAN membership and basic network connectivity.

## Project Status

**Status:** In Progress

The topology and configuration will be added and tested in Cisco Packet Tracer. Screenshots and test results will be included as the project develops.

---

Created as part of my Cisco Networking and Cybersecurity learning journey.
