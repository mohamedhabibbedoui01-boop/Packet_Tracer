# VLAN-Based Network

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Segment a small organization into separate logical Layer 2 networks.

## Proposed topology

One or two switches and at least three groups of end devices, such as Admin, IT, and Guest.

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

Create VLANs; assign access ports; label ports; connect switches; configure trunks when multiple switches carry the VLANs; verify that devices in the same VLAN communicate.

## Verification plan

show vlan brief; show interfaces trunk; ping between same-VLAN devices; confirm different VLANs are isolated before routing is configured.

## Suggested folder contents

```text
02-vlan-based-network/
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

Use a fictional organization and private RFC1918 addressing.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
