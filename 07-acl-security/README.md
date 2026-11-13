# ACL Security

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Control traffic between network segments using standard and extended access control lists.

## Proposed topology

Router or Layer 3 device with at least two networks or VLANs and multiple test hosts.

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

Define a traffic policy first; configure standard ACLs for source-based filtering and extended ACLs for protocol/port-aware filtering; apply ACLs in the correct direction and interface; test allowed and denied traffic.

## Verification plan

show access-lists; show ip interface; show running-config; test permitted and blocked pings or application traffic; check ACL hit counters where supported.

## Suggested folder contents

```text
07-acl-security/
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

Use least privilege. Document the implicit deny and ensure you do not accidentally block required management traffic.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
