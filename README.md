# Cisco Packet Tracer — Networking & Security Portfolio

A hands-on portfolio of Cisco Packet Tracer labs focused on routing, switching, network services, access control, and monitoring.

**Current focus:** Build and document the ten labs below in a progressive order. A lab is marked **Completed** only after its Packet Tracer file, configuration, screenshots, and verification results have been added and checked.

## Project roadmap

| # | Project | Main skills | Status |
|---|---|---|---|
| 01 | [Secure Router Configuration](01-secure-router-configuration/README.md) | Device hardening, passwords, SSH | Planned |
| 02 | [VLAN-Based Network](02-vlan-based-network/README.md) | VLANs, access ports, trunks | Planned |
| 03 | [Inter-VLAN Routing](03-inter-vlan-routing/README.md) | Router-on-a-stick, 802.1Q | Planned |
| 04 | [SSH and Device Access](04-ssh-and-device-access/README.md) | Local users, SSH, secure management | Planned |
| 05 | [Port Security](05-port-security/README.md) | Switch port security, MAC limits | Planned |
| 06 | [Static Routing](06-static-routing/README.md) | Routing tables, next hops, default routes | Planned |
| 07 | [ACL Security](07-acl-security/README.md) | Standard and extended ACLs | Planned |
| 08 | [DHCP and DNS](08-dhcp-and-dns/README.md) | Address allocation, name resolution | Planned |
| 09 | [NAT](09-nat/README.md) | Static NAT, dynamic NAT, PAT | Planned |
| 10 | [Network Monitoring](10-network-monitoring/README.md) | Syslog, SNMP concepts, show commands | Planned |

## Repository structure

```text
Packet_Tracer/
├── 01-secure-router-configuration/
├── 02-vlan-based-network/
├── 03-inter-vlan-routing/
├── 04-ssh-and-device-access/
├── 05-port-security/
├── 06-static-routing/
├── 07-acl-security/
├── 08-dhcp-and-dns/
├── 09-nat/
├── 10-network-monitoring/
├── LAB1 RouterSecurityconfig(1).pkt
├── LAB1 RouterSecurityconfig(1).bak
└── README.md
```

Each project folder contains a project brief and a checklist. As you complete a lab, add:
- `project.pkt` — the working Packet Tracer simulation.
- `configs/` — sanitized device configurations.
- `screenshots/` — topology and test evidence.
- `tests.md` — test cases, expected results, and actual results.

## Recommended workflow

1. Read the project brief and draw the topology.
2. Plan the IP addressing and VLANs before configuring devices.
3. Build the topology in Cisco Packet Tracer.
4. Configure one feature at a time and save checkpoints.
5. Verify connectivity and security behaviour with suitable tests.
6. Save the `.pkt` file, sanitized configurations, screenshots, and test results.
7. Update the project status here only when the evidence is present.

## Existing router-security files

The repository currently includes [LAB1 RouterSecurityconfig(1).pkt](LAB1%20RouterSecurityconfig(1).pkt) and its `.bak` companion in the repository root. They are retained as existing artifacts; their topology and configuration have not yet been independently verified. Review them in Packet Tracer before treating Project 01 as completed or moving them into its folder.

## Tools

- Cisco Packet Tracer (record the version used for each lab).
- Cisco IOS-style CLI commands supported by the selected simulated devices.
- Markdown for documentation and Git for version control.

## Safety and publication

Use simulated networks or infrastructure you own or are authorized to administer. Never publish real credentials, private keys, sensitive IP plans, or confidential network diagrams. Use fictional credentials in demonstrations and redact secrets from configuration files.

---

*Design. Configure. Test. Document. Improve.*
