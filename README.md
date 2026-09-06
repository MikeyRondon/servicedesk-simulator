# ServiceDesk Simulator - IT Support Portfolio

Hands-on IT help desk simulations focused on ticket triage, troubleshooting, user communication, incident resolution, and technical documentation.

## Overview

This repository documents IT support scenarios completed in **ServiceDesk Simulator**, a simulated help desk environment.

The project is designed to demonstrate my troubleshooting process rather than simply record completed tickets. Each case study documents the reported problem, investigation, troubleshooting steps, resolution, verification, and relevant lessons learned.

Scenarios include user account issues, network outages, VPN connectivity, DNS troubleshooting, print services, and workstation configuration.

## Case Studies

| Ticket | Priority | Issue | Case Study |
|---|---|---|---|
| INC0012855 | High | Expired password / login failure | [Password Expiration and Login Failure](docs/password-reset.md) |
| INC0012858 | Critical | Floor-wide network outage | [Floor-Wide Network Outage](docs/floor-network-outage.md) |
| NET17858785086451 | High | VPN connectivity and DNS resolution | [VPN Connectivity and DNS Resolution](docs/vpn-connectivity.md) |
| INC0012870 | High | Building-wide printer outage | [Building-Wide Printer Outage](docs/print-server-outage.md) |
| INC0012865 | High | Incorrect time zone and system clock | [Workstation Time Zone and Clock Synchronization](docs/workstation-time-sync.md) |

## Skills Practiced

- Help desk ticket triage and prioritization
- Troubleshooting based on issue scope
- Active Directory-style user and authentication management
- Password resets and identity verification
- Network infrastructure troubleshooting
- Network switch troubleshooting
- VPN and remote-access troubleshooting
- DNS troubleshooting
- Windows command-line utilities
- Remote workstation support
- Print server troubleshooting
- System time and time-zone configuration
- Internal technical documentation review
- End-user communication
- Incident resolution and verification
- Technical documentation

## Troubleshooting Approach

Throughout these simulations, I practiced a structured troubleshooting process:

1. Identify the user's symptoms and business impact.
2. Determine the scope of the issue.
3. Review relevant internal documentation.
4. Establish likely causes based on available evidence.
5. Test the lowest-risk and most relevant troubleshooting steps first.
6. Make one change at a time when possible.
7. Verify the result technically.
8. Confirm restoration of service with the user.
9. Document the resolution and lessons learned.

Not every troubleshooting path led directly to the solution. Where applicable, the case studies document unsuccessful steps and what I learned from them.

## Repository Structure

```text
servicedesk-simulator/
├── README.md
├── docs/
│   ├── password-reset.md
│   ├── floor-network-outage.md
│   ├── vpn-connectivity.md
│   ├── print-server-outage.md
│   └── workstation-time-sync.md
└── screenshots/
    └── Supporting screenshots from each simulation
```

## Environment

The scenarios in this repository were completed using **ServiceDesk Simulator**, which provides a simulated enterprise IT environment with tools for areas such as:

- User and directory management
- Remote workstation support
- Server and network infrastructure
- Internal documentation
- Asset management
- Ticket management and user communication

## Project Status

**In Progress**

This repository will continue to grow as I complete additional ServiceDesk Simulator tickets and expand my hands-on IT support troubleshooting experience.

---

> **Note:** All tickets, users, systems, credentials, and company resources shown in this repository are part of a simulated training environment. These case studies represent hands-on practice and are not presented as professional support work performed for an employer.
