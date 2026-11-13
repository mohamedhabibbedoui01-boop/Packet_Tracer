# Secure Router Configuration

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Harden a simulated Cisco router and establish a secure baseline for administrative access.

## Proposed topology

One router and one management PC connected through a switch or directly, as supported by the selected Packet Tracer devices.

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

Set a hostname; configure encrypted privileged access; create a local administrative user; configure console and VTY access; disable unused services where supported; save and review the configuration.

## Verification plan

show running-config; show ip interface brief; show users; test permitted management access and confirm insecure access is not enabled.

## Suggested folder contents

```text
01-secure-router-configuration/
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

Never commit real passwords. Use fictional lab credentials and redact secrets in published configs.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
