# NAT

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Translate private inside addresses to an external simulated network.

## Proposed topology

Router with inside LAN, outside/WAN segment, and an external test server or network.

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

Identify inside and outside interfaces; configure and test PAT (NAT overload); optionally compare static and dynamic NAT; generate traffic from inside clients; inspect translations and counters.

## Verification plan

show ip nat translations; show ip nat statistics; show access-lists; ping or access the simulated external server; verify translations are created.

## Suggested folder contents

```text
09-nat/
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

Use a simulated external network only. Document the translation policy and avoid real public IPs or credentials.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
