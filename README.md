# IT Support Specialist to Cloud Engineer

**Plan date:** November 5, 2026 | **Study pace:** 8–10 hours/week | **Core path:** approximately 15–20 months.

This is a certification-aligned, home-lab-first learning path. Every exam target has hands-on objectives, a final project, and an exit gate. Passing an exam does not replace practical competence.

## Starting point
- Current role: IT Support Specialist
- Existing lab: Windows Server domain controller and one domain-joined Windows client
- Primary cloud: Microsoft Azure
- Destination: Cloud Engineer

## Certification targets
| Phase | Certification |
|---|---|
| 00 | No exam — inventory and safely prepare lab |
| 01 | CompTIA Network+ N10-009 (CCNA is an alternative) |
| 02–03 | Microsoft Windows Server Administrator Associate — AZ-802 |
| 04 | Microsoft Azure Fundamentals — AZ-900 |
| 05 | CompTIA Security+ (current exam version at booking) |
| 06 | Microsoft Azure Administrator Associate — AZ-104 |
| 07 | CompTIA Linux+ (RHCSA is an alternative) |
| 08 | HashiCorp Terraform Associate 004 |
| 09 | Microsoft DevOps Engineer Expert — AZ-400 OR Azure Solutions Architect Expert — AZ-305 |
| 10 | AWS Solutions Architect Associate — SAA-C03 (optional) |

Choose one alternative, not both: Network+ or CCNA; Linux+ or RHCSA; AZ-400 or AZ-305. AWS is an optional second-cloud extension.

## How to use this repository
1. Follow `ROADMAP.md` in order.
2. Inventory your existing DC and client before deleting or rebuilding anything.
3. Complete each phase README and lab checklist.
4. Document substantial work with `templates/LAB-REPORT.md`.
5. Map study to the official exam guide linked in each phase.
6. Sit the exam only after the readiness gate is met.
7. Publish sanitized evidence only.

## Weekly schedule
- 3 hours official learning and exam objectives
- 3–4 hours hands-on labs
- 1–2 hours practice questions and recall
- 1 hour documentation and portfolio

## Safety
Keep AD DS, DNS, DHCP, SMB, RDP, WinRM, and hypervisor management on private networks. Use synthetic data. Snapshot before destructive changes. Check Windows licensing/evaluation terms. Set cloud budgets and alerts. Never commit passwords, tokens, private keys, `.env`, Terraform state, or unredacted logs.

## Definition of done
You can repeat the work without a step-by-step tutorial, explain why it works, troubleshoot a deliberate failure, and show sanitized evidence. This roadmap improves readiness but cannot guarantee employment.
