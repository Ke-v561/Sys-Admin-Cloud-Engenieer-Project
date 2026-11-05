# Phase 00 — Reset and Rebuild the Home Lab

## Phase purpose
Mission-critical foundation. You have a Windows Server Domain Controller and one domain-joined Windows PC, but previous configuration is undocumented. Rebuild from a known-good baseline so later labs begin from systems you understand.

## Credential and anticipated price
- **Credential:** None — required foundation phase
- **Exam price:** $0 exam fee assuming existing hardware and valid OS licensing
- **Price snapshot:** November 5, 2026; before applicable taxes/fees. Confirm current price and exam version before purchase.
- **Other costs:** optional study materials, retakes, and cloud consumption are additional.

## Estimated duration
1–2 weeks at 6–10 study hours per week.

## Starting requirements
- IT Support Specialist-level Windows familiarity.
- Access to the server VM/physical host and Windows client.
- Confirm console/recovery access before deleting anything.

## Phase objectives
- Inventory hardware, hypervisor, VM resources, IP ranges, DNS, domain, and licensing.
- Back up anything worth retaining, then reset/reinstall server and client.
- Understand server roles, static addressing, DNS, AD DS, domain join, local vs domain accounts, and basic Windows administration.
- Draw topology and record decisions.

## End goal
A clean, repeatable lab with one Windows Server Domain Controller and one domain-joined Windows client. Explain how the client locates the DC, authenticates, resolves DNS, and receives policy.

## Hands-on work
- Record current lab inventory and topology.
- Install/reset Windows Server; configure hostname, updates, time, static IP.
- Install AD DS and promote to a new test forest/domain.
- Configure DNS and verify forward lookup; understand reverse zones.
- Create test OUs, users, and security groups.
- Join a clean Windows client to the domain.
- Verify domain sign-in, DNS, secure channel, and GPO processing.
- Create snapshot/backup and document recovery.

## Final project
Publish a sanitized Lab Baseline Build: topology, VM specifications, build sequence, AD structure, DNS settings, verification commands, and recovery notes.

## Completion requirements
- Server and client rebuild documented.
- Domain join works after reboot.
- Client uses the DC for domain DNS.
- Test user can sign in.
- Understand sanitized outputs from `nslookup`, `ipconfig /all`, `whoami /all`, `gpresult /r`, and `Test-ComputerSecureChannel`.
- Explain what breaks if client uses unrelated DNS.
- Backup/snapshot and recovery notes exist.

## Exam / skills alignment
Prepares for Windows, identity, and networking prerequisites expected in AZ-104 and later hybrid identity labs. No separate certification.

## Official resources
- [AD DS documentation](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/)
- [Windows DNS documentation](https://learn.microsoft.com/en-us/windows-server/networking/dns/dns-top)
- [Windows Server documentation](https://learn.microsoft.com/en-us/windows-server/)

Use a private test namespace such as `ad.example.test`; never use a real public domain you do not own. Do not publish passwords or sensitive identifiers.

## Safety and cost reminder
Use synthetic data, protect secrets, set cloud budgets/alerts where available, and delete billable resources after labs.
