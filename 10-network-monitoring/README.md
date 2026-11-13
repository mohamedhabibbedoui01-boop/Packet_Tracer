# Network Monitoring

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Observe device status and network events using Packet Tracer-supported monitoring features.

## Proposed topology

A small routed and switched topology, a monitoring PC or server, and supported simulated services.

## Implementation checklist

- [ ] Draw and save the topology.
- [ ] Plan and document the IP addressing scheme.
- [ ] Build the topology in Cisco Packet Tracer.
- [ ] Configure the required devices and features.
- [ ] Save the working simulation as `project.pkt`.
- [ ] Export sanitized configurations into `configs/`.
- [ ] Capture the topology and verification results in `screenshots/`.
- [ ] Record expected and actual results in `tests.md`.
- [ ] Update the main portfolio README when the lab is verified.

## Configuration tasks

Establish a baseline; practise show commands for interfaces, routes, and MAC tables; configure Syslog and/or SNMP if supported by the selected devices; generate a controlled event; record what can and cannot be observed in Packet Tracer.

## Verification plan

show logging; show interfaces; show ip route; inspect server logs or SNMP service where available; compare device state before and after a controlled event.

## Suggested folder contents

```text
10-network-monitoring/
├── README.md
├── project.pkt
├── configs/
│   └── device-configs.txt
├── screenshots/
│   ├── topology.png
│   └── verification.png
└── tests.md
```

## Safety and documentation

Use lab-only community strings or credentials. State clearly which monitoring features are simulated or unsupported.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
