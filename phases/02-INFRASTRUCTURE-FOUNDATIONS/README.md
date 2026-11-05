# Phase 02 — Infrastructure Foundations for Cloud Administration

## Phase purpose
Mission-critical prerequisite. AZ-104 expects practical familiarity with operating systems, networking, servers, virtualization, PowerShell, Azure CLI, and identity. Use the domain lab to close these gaps before the Azure administrator exam.

## Credential and anticipated price
- **Credential:** No separate certification; required preparation for AZ-104
- **Exam price:** $0 exam fee
- **Price snapshot:** November 5, 2026; before applicable taxes/fees. Confirm current price and exam version before purchase.
- **Other costs:** optional study materials, retakes, and cloud consumption are additional.

## Estimated duration
6–10 weeks at 6–10 study hours per week.

## Starting requirements
- Phase 00 complete.
- AZ-900 learning objectives completed (exam optional).
- Windows Server and client access.

## Phase objectives
- Networking: IPv4/IPv6, subnetting, routing, DNS, DHCP, NAT, VPN, ports, firewall/NSG concepts, troubleshooting.
- Windows Server: roles, services, event logs, storage, patching, remote administration, backup/recovery.
- Identity: AD DS users/groups/OUs, GPO, least privilege, authentication/authorization, on-prem vs cloud identity.
- PowerShell: variables, objects, pipelines, filtering, loops, functions, modules, remoting, error handling.
- Virtualization: VMs, virtual switches, checkpoints, sizing, guest networking.
- Introductory Azure CLI.

## End goal
Independently build and troubleshoot a small Windows domain, explain network and identity flows, automate administration with PowerShell, and understand concepts that map to Azure resources.

## Hands-on work
- Create OUs, users, groups, delegated permissions; test least privilege.
- Create/link a GPO and verify with `gpresult`.
- Configure DHCP only in an isolated lab if safe; otherwise document a scope design.
- Diagnose DNS, gateway/subnet, domain join, time skew, and secure-channel failures.
- Use PowerShell to inventory computers, users, services, event logs, and disk space.
- Practice remote management and event-log investigation.
- Draw subnet/routing diagram and calculate subnets.

## Final project
Small Business Infrastructure Runbook: topology, IP plan, AD design, DNS/DHCP design, GPO baseline, least-privilege matrix, scripts, and troubleshooting decision trees.

## Completion requirements
- Restore/rebuild from documented steps.
- Complete five troubleshooting scenarios independently.
- Explain DNS resolution and domain authentication end to end.
- Demonstrate user/group/OU/GPO administration.
- Write and explain three safe PowerShell scripts with error handling.
- Explain subnetting, routing, ports, and firewall rules relevant to Azure VNets.
- Publish sanitized runbook.

## Exam / skills alignment
Directly supports AZ-104 prerequisites and its identity/governance, networking, compute, storage, monitoring, and maintenance skill areas.

## Official resources
- [AZ-104 certification and prerequisites](https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/)
- [PowerShell documentation](https://learn.microsoft.com/en-us/powershell/)
- [Windows Server documentation](https://learn.microsoft.com/en-us/windows-server/)
- [Azure Virtual Network overview](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview)



## Safety and cost reminder
Use synthetic data, protect secrets, set cloud budgets/alerts where available, and delete billable resources after labs.
