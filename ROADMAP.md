# Roadmap and phase gates

Estimated total: **9–15 months** at 6–10 hours/week, depending on prior experience, lab capacity, and exam timing. Treat the durations as ranges, not deadlines.

| Phase | Focus | Typical time | Credential |
|---|---|---:|---|
| 00 | Lab reset and baseline | 1 week | None |
| 01 | Networking foundations | 3–5 weeks | None |
| 02 | Windows Server and Active Directory | 5–7 weeks | None |
| 03 | Systems administration | 4–6 weeks | None |
| 04 | Cloud fundamentals | 2–3 weeks | AZ-900 optional |
| 05 | Security foundations | 3–5 weeks | Security+ optional |
| 06 | Azure administration | 8–12 weeks | AZ-104 |
| 07 | Linux and containers | 4–6 weeks | None |
| 08 | Terraform and IaC | 4–6 weeks | Terraform Associate optional |
| 09 | Cloud engineering capstone | 4–6 weeks | Portfolio project |
| 10 | AWS extension | 4–8 weeks | AWS SAA optional |

## Why this order?
Networking, identity, Windows administration, and operational discipline are prerequisites to understanding cloud infrastructure. Azure is the primary platform because the existing lab is Microsoft-oriented and Azure provides a natural bridge from on-premises identity and Windows administration. Linux, containers, and IaC are added before the capstone because cloud engineering extends beyond administering virtual machines.

## Gate rule
Do not skip a phase just because its certification is optional. The knowledge and practical exit criteria remain mandatory. Certifications are checkpoints, not substitutes for labs.

## Lab growth plan
- **Stage A — Existing equipment:** retain the current domain controller and joined client long enough to inventory and document them. Create a rollback plan before rebuilding.
- **Stage B — Add virtual machines:** if host resources allow, add a second Windows Server VM as a member/file server and a second client. A second physical server is not required.
- **Stage C — Add Linux:** add one Ubuntu Server VM for SSH, services, logs, firewall, and Docker labs.
- **Stage D — Cloud:** use Azure free allowances/trial only after checking current terms, budgets, and spending alerts. Tear down resources after each lab.
- **Stage E — IaC:** store sanitized Terraform/Bicep code in Git; never commit state files or secrets.

## Phase dependencies
`00 → 01 → 02 → 03 → 04 → 05 → 06 → 07 → 08 → 09 → 10 (optional)`
