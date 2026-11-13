# Inter-VLAN Routing

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Enable controlled Layer 3 communication between VLANs.

## Proposed topology

One router with an Ethernet trunk to a managed switch (router-on-a-stick), multiple VLANs, and end devices.

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

Create VLANs and trunk; configure router subinterfaces with 802.1Q encapsulation and gateway addresses; configure end-device gateways; test routing between VLANs.

## Verification plan

show ip interface brief; show ip route; show interfaces trunk; ping gateways and permitted hosts in other VLANs.

## Suggested folder contents

```text
03-inter-vlan-routing/
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

Document which VLANs should communicate; do not assume all inter-VLAN traffic should be allowed.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
