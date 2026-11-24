
# IT Homelab | Infrastructure & Systems Administration

## About This Homelab

Welcome to my IT Homelab portfolio!

I am an Information Technology student at Arizona State University, building a hands-on homelab to develop and demonstrate practical experience in networking, virtualization, systems administration, and IT security.

This environment allows me to simulate real-world business infrastructure, configure enterprise technologies, troubleshoot technical issues, and apply concepts learned through coursework and independent study.

This repository documents my projects, technical implementations, challenges, and lessons learned.

## Lab Infrastructure

| Component | Technology |
|---|---|
| Hypervisor | Proxmox Virtual Environment |
| Router | GL.iNet Beryl |
| Network Switch | Cisco Catalyst Managed Switch |
| Domain Controller | Windows Server (DC01) |
| Domain Workstation | Windows Client (PC01) |
| Home Automation | Home Assistant OS |
| Lab Domain | bkirsch.local |

## Network Architecture

The homelab uses a dedicated router and managed switch to provide network connectivity to a Proxmox virtualization host running multiple virtual machines.

**Network topology diagram:** To be added.

## Homelab Projects

Each project contains its own documentation covering objectives, implementation, troubleshooting, validation, and supporting screenshots.

| Project | Status | Documentation |
|---|---|---|
| 01 — Active Directory Enterprise Environment | Core Build Completed | [View Project](projects/01-active-directory/README.md) |
| 02 — Help Desk Ticketing Simulation | Planned | Coming Soon |
| 03 — OPNsense Firewall & Network Segmentation | Planned | Coming Soon |
| 04 — Linux Server Administration | Planned | Coming Soon |
| 05 — Monitoring & Security | Planned | Coming Soon |

### Project 01 — Active Directory Enterprise Environment

Designed and configured a simulated business Active Directory environment for a fictional organization, Desert Peak Solutions.

Implemented organizational units, employee accounts, security groups, Group Policy Objects, and delegated administrative permissions. Integrated a domain-joined workstation to practice centralized administration and troubleshooting.

[View Project 01 Documentation](projects/01-active-directory/README.md)

## Technical Skills & Technologies

- **Virtualization:** Proxmox VE, virtual machines, virtual networking
- **Networking:** TCP/IP, DNS, DHCP, switching, network troubleshooting
- **Windows Administration:** Windows Server, Active Directory, Group Policy
- **Identity & Access Management:** Security groups, permissions, delegated administration
- **Infrastructure Documentation:** Network diagrams, implementation guides, technical troubleshooting

## Future Development

I plan to continue expanding the homelab with network segmentation, firewall administration, Linux services, infrastructure monitoring, backup and recovery, and additional enterprise IT simulations.

Projects will be documented as they progress, with supporting evidence and lessons learned.

---

*This repository represents a personal educational lab environment developed for hands-on learning and professional skill development.*
