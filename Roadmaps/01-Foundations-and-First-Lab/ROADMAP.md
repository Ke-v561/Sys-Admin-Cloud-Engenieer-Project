# 01 — Foundations & First Lab

**Starting assumption:** no existing cloud account, virtualization platform, or home lab.

## Phase 1 — Understand your starting point
- [ ] Record your PC specifications: CPU, RAM, storage, Windows edition and available disk space.
- [ ] Learn the difference between hardware, operating system, application, server, client and virtual machine.
- [ ] Learn basic files/folders, Task Manager, Device Manager, Windows Update and Event Viewer.
- [ ] Create a folder for lab notes and a separate folder for project evidence.

**Deliverable:** `my-lab-inventory.md` with specs and a simple diagram of your current network. Do not include public IPs, passwords or sensitive network details.

## Phase 2 — Networking essentials
- [ ] Explain IP address, subnet mask, default gateway, DNS and DHCP in your own words.
- [ ] Practice `ipconfig`, `ping`, `tracert`/`traceroute`, and `nslookup` on your own system.
- [ ] Identify your PC's local IP, gateway and DNS servers.
- [ ] Explain the difference between a private IP and public IP.

**Deliverable:** a troubleshooting worksheet with command, purpose, sample output and interpretation.

## Phase 3 — Virtualization basics
- [ ] Learn what a hypervisor does and the difference between Type 1 and Type 2 virtualization.
- [ ] Check whether your PC supports virtualization and whether it is enabled in firmware.
- [ ] Choose a beginner route: a desktop hypervisor on a capable PC, or a cloud sandbox/free learning environment if local resources are limited.
- [ ] Create one disposable Linux or Windows evaluation VM only after checking system requirements and licensing.
- [ ] Learn snapshots/checkpoints, virtual CPU/RAM/disk allocation, virtual networking and safe shutdown.
- [ ] Take a snapshot, make a harmless change, revert, and document what happened.

**Do not** install Proxmox or buy hardware as a prerequisite. It can be a later upgrade, not a starting requirement.

## Phase 4 — Safety and documentation
- [ ] Use fictional test data and non-production systems.
- [ ] Learn why backups, updates, least privilege and strong unique passwords matter.
- [ ] Never publish credentials, license keys, API tokens or screenshots containing personal information.
- [ ] Write a one-page lab build guide that another beginner could follow.

## Finish line
You can describe your computer's basic specs, explain basic network settings, create and revert a VM (or document an approved alternative), and explain your safety precautions. No certification required for this path.
