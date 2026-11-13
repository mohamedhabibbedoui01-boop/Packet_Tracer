# Static Routing

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Connect multiple IP networks using manually configured routes.

## Proposed topology

Two or three routers, separate LANs, and point-to-point links between routers.

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

Plan non-overlapping subnets; configure interface addresses; bring interfaces up; add static routes and optionally a default route; inspect routing tables; test end-to-end traffic.

## Verification plan

show ip interface brief; show ip route; show running-config; ping and traceroute between LANs; test behaviour after a link is disabled and restored.

## Suggested folder contents

```text
06-static-routing/
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

Keep the topology and addressing fictional and clearly documented.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
