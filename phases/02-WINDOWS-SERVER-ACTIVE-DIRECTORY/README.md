# Phase 02 — Windows Server and Active Directory

## Purpose
Build and administer a Windows domain from the ground up. This is a core systems skill, not an optional side topic.

## End goal
Build a small, documented Windows domain with OUs, least-privilege groups, GPOs, DNS, joined client, and a tested backup/restore exercise.

## Prerequisites
- Phases 00–01 complete; Windows Server installation media and a private virtual network.

## Certification
**None.** No certification required.

## Estimated duration
**5–7 weeks** at 6–10 hours per week. Adjust based on demonstrated competence, not calendar pressure.

## Learning objectives and hands-on labs
1. Install a fresh Windows Server VM and configure a static IP and hostname.
2. Install AD DS and promote the server to a new forest using a private lab DNS name.
3. Create OUs, users, security groups, service accounts, and delegated administration.
4. Join a Windows client to the domain; test sign-in and domain resource access.
5. Create and link GPOs for password/account policy, workstation security, mapped drives, and a controlled test setting.
6. Configure DNS zones/records and troubleshoot client DNS registration.
7. Understand Kerberos at a practical level; inspect time sync, tickets, and common authentication failures.
8. Explore FSMO roles, replication concepts, Sites and Services, and event logs in a single-DC lab (document multi-DC concepts; do not fake replication).
9. Back up System State and document authoritative/non-authoritative recovery concepts.

## Final project
Build a small, documented Windows domain with OUs, least-privilege groups, GPOs, DNS, joined client, and a tested backup/restore exercise.

## Completion criteria
- [ ] Can create and manage users/groups/OUs without a walkthrough.
- [ ] Can diagnose domain join, DNS, GPO, lockout, and authentication issues.
- [ ] Can explain the relationship between AD DS, DNS, Kerberos, and Group Policy.
- [ ] Can restore or recover the lab using documented steps.

## Cost planning
- No exam fee required. Check OS licensing/evaluation terms and any optional hardware costs.

## Official references
- Microsoft Learn: https://learn.microsoft.com/training/
- Microsoft technical documentation: https://learn.microsoft.com/docs/
- Use the current provider exam guide where a certification is listed; versions and objective weights can change.
