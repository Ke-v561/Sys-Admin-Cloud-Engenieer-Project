# Phase 00 — Lab reset and baseline

## Purpose
Inventory the existing Windows Server domain controller and joined client before changing anything. Record host hardware, hypervisor, VM resources, IPs, DNS, domain name, roles, users/groups, GPOs, shares, DHCP scope (if present), backup status, and recovery credentials. Export/document only what is safe. Create snapshots/backups and verify console access. Decide whether to retain the domain or rebuild it in an isolated lab. Do not delete the existing DC until you have a tested recovery path.

## End goal
Produce a one-page current-state diagram, asset inventory, and safe rebuild checklist.

## Prerequisites
- A working hypervisor or virtualized environment and access to the existing Windows Server and client. No rebuild until inventory and recovery access are confirmed.

## Certification
**None.** No certification required.

## Estimated duration
**1 week** at 6–10 hours per week. Adjust based on demonstrated competence, not calendar pressure.

## Learning objectives and hands-on labs
1. Create a current-state diagram and inventory.
2. Confirm hypervisor console access and local administrator recovery.
3. Back up critical lab configuration and take snapshots.
4. Create a private isolated virtual switch/network for the lab.
5. Write a rebuild plan and rollback plan.

## Final project
Produce a one-page current-state diagram, asset inventory, and safe rebuild checklist.

## Completion criteria
- [ ] Can describe every current VM and its role.
- [ ] Can log in through console if network/DNS fails.
- [ ] Has a verified rollback/recovery route.
- [ ] Has isolated lab networking and a documented plan.

## Cost planning
- No exam fee required. Check OS licensing/evaluation terms and any optional hardware costs.

## Official references
- Microsoft Learn: https://learn.microsoft.com/training/
- Microsoft technical documentation: https://learn.microsoft.com/docs/
- Use the current provider exam guide where a certification is listed; versions and objective weights can change.
