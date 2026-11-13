# Port Security

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Reduce unauthorized endpoint connections on selected switch access ports.

## Proposed topology

One access switch and several PCs, including an extra test device for violation testing.

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

Enable port security on selected access ports; choose a maximum MAC count; practise sticky or manually configured secure MAC addresses; select and document a violation mode; test a violation and recovery.

## Verification plan

show port-security; show port-security interface [interface-id]; show mac address-table; connect an unauthorized test device and observe the configured response.

## Suggested folder contents

```text
05-port-security/
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

Only test on your own simulated switch. Explain the chosen violation mode and how to recover safely.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
