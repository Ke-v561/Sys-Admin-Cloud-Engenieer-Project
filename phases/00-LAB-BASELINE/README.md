# Phase 00 — Lab reset and baseline

## Purpose
Inventory the existing Windows Server DC and joined client before changing anything. Do not delete/rebuild the DC until current state and recovery access are documented.

## Certification target
**No certification**

## Estimated duration
**1 week** at 8–10 hours/week, including learning, labs, review, exam preparation, and the exam.

## End goal
Deliver a sanitized inventory, diagram, and safe rebuild plan.

## Prerequisites
- Access to existing hypervisor, Windows Server DC, and joined client.

## Official exam objectives
No exam.

## Hands-on lab objectives
1. Record host/hypervisor, VM resources, virtual switches, IPs, DNS, domain, roles, OUs, users/groups, GPOs, shares, DHCP, backups, and recovery credentials.
2. Draw a sanitized network/domain diagram.
3. Confirm console access and a local recovery admin account.
4. Create snapshots/backups and a rollback plan.
5. Create an isolated lab virtual network and test that management/domain services are not internet-exposed.

## Final project
Deliver a sanitized inventory, diagram, and safe rebuild plan.

## Completion criteria
- [ ] Can describe each VM and role.
- [ ] Can access server console if DNS/network fails.
- [ ] Has a documented recovery route and isolated lab network.

## Exam readiness gate
- [ ] Current official exam domains reviewed.
- [ ] Mapped labs completed and documented.
- [ ] Can explain concepts without notes.
- [ ] Weak-area labs repeated without a walkthrough.
- [ ] Practice performance consistently meets personal readiness threshold.
- [ ] Exam version, price, policy, and prerequisites rechecked before booking.

## Cost and safety
Verify regional exam price at checkout. Set cloud budgets before deployment and remove resources afterward. Check OS licensing/evaluation terms. Never expose management services or publish secrets.
