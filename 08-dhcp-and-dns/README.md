# DHCP and DNS

**Status:** Planned — this folder is a project brief, not evidence of a completed lab.

## Objective

Provide automatic IP configuration and name resolution to simulated clients.

## Proposed topology

Router or server providing DHCP, a DNS server, one or more switches, and client PCs.

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

Create DHCP scopes/pools with correct network, mask, gateway, and DNS options; exclude reserved addresses; configure DNS records on a supported server; obtain leases on clients; resolve a test hostname.

## Verification plan

show ip dhcp binding; show ip dhcp pool; ipconfig /all on clients; ping the gateway; use nslookup or a browser test if supported by the Packet Tracer client.

## Suggested folder contents

```text
08-dhcp-and-dns/
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

Use reserved fictional domains and private lab addresses; do not publish real internal DNS names.

Record the Packet Tracer version and device models used. Include only configurations you have personally tested. Remove passwords, keys, and other secrets before publishing.

## Learning notes

After completing the lab, add:
- What you learned.
- What failed and how you fixed it.
- Any Packet Tracer limitations you encountered.
- What you would improve in a second version.
