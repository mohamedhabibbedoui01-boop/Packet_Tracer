# SSH and Device Access

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Configure secure remote administration of simulated network devices.

## Proposed topology

One router or switch, one management PC, and a reachable management interface.

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

Set hostname and domain name; create a local user; generate RSA keys if supported; configure SSH version 2; restrict VTY lines to SSH and local login; test authorized and unauthorized access.

## Verification plan

show ip ssh; show users; inspect line vty configuration; connect using an SSH client from the management PC; verify Telnet is not accepted where disabled.

## Suggested folder contents

```text
04-ssh-and-device-access/
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

Use lab-only credentials. Do not publish passwords, private keys, or real management addresses.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
