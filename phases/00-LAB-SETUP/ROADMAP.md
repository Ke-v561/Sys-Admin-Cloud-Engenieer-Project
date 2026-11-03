# Phase 0 — Home Lab Inventory and Safe Setup

**Outcome:** A documented, recoverable lab that does not disrupt household devices.

## Project 0.1 — Inventory the environment

1. Record host model, CPU, RAM, storage, and network adapters.
2. Record hypervisor version and current VMs/containers.
3. Record virtual bridges, physical NIC assignments, router, firewall, DHCP, and DNS.
4. Record current IP ranges and identify overlaps.
5. Identify backup/snapshot method and recovery access.

**Expected result:** `inventory.md` lists the current state accurately.

## Project 0.2 — Design an isolated lab

1. Draw the existing home network.
2. Draw a proposed lab network.
3. Select non-overlapping subnets.
4. Identify management, server, and client segments.
5. Define permitted traffic between segments.
6. Document how to revert changes if connectivity is lost.

**Expected result:** A network diagram and IP plan.

## Acceptance criteria
- [ ] Inventory complete
- [ ] Network diagram complete
- [ ] No subnet overlap
- [ ] Recovery procedure documented
- [ ] Household network protected

Do not change live router/firewall settings until the current configuration is backed up and you understand the impact.
