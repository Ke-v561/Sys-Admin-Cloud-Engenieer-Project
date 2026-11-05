# From IT Support Specialist to Cloud Engineer

A hands-on, certification-aligned roadmap for a learner starting in IT Support with a home lab containing a Windows Server Domain Controller and one domain-joined Windows PC.

**Recommended route: Azure first, AWS later as an optional extension.** Azure is the most coherent first platform because the existing Windows domain lab provides a practical bridge into Windows Server, identity, DNS, networking, and hybrid administration. This is a learning-sequence recommendation, not a claim that Azure is universally better than AWS.

**Study pace:** 6–10 hours/week. **Estimated duration:** 9–15 months; AWS extension adds roughly 2–4 months.

## Roadmap

| Phase | Purpose | Certification | US exam price* |
|---|---|---|---:|
| 00 | Reset and document the lab; mission-critical foundation | None | $0 |
| 01 | Cloud and Azure fundamentals | AZ-900 (recommended, optional) | $99 |
| 02 | Networking, Windows Server, identity, PowerShell foundations | None; mission-critical prerequisite | $0 |
| 03 | Vendor-neutral security foundation | Security+ SY0-701 | $439 |
| 04 | Azure administration | AZ-104 | $165 |
| 05 | Infrastructure as Code | Terraform Associate 004 | $70.50 |
| 06 | Multi-cloud architecture extension | AWS SAA-C03 (optional) | $150 |

**Core exam budget:** $674.50 skipping AZ-900; $773.50 including AZ-900. With AWS extension: $824.50 skipping AZ-900; $923.50 including it. These totals assume one attempt per exam and exclude taxes, retakes, training, hardware, and cloud usage.

*US exam price snapshot: November 5, 2026. Confirm prices and exam versions with official providers before purchase.*

## How to use
1. Start with Phase 00 and rebuild from a known-good state.
2. Complete each phase's objectives, labs, final project, and exit criteria.
3. Save sanitized evidence in the phase folder.
4. Use each `EXAM-READINESS.md` before buying an exam voucher.
5. Update `PROGRESS-TRACKER.md` with dates and evidence links.

Every phase is either a certification phase or mission-critical prerequisite. Each phase README includes objectives, end goal, exam alignment, anticipated price, time estimate, labs, and completion criteria. Exam blueprints change; official study guides are authoritative.

## Study cadence
- 2–3 hours: concepts and notes.
- 3–5 hours: hands-on labs.
- 1 hour: troubleshooting and documentation.
- 1 hour: review/practice questions.

## Safety and cost
Use synthetic identities and test data. Never commit secrets, credentials, private keys, tokens, or Terraform state. Set cloud budgets/alerts where available, understand alerts may not cap spending, and delete lab resources after use. Do not expose RDP/SSH or domain controllers directly to the public internet.

## Official sources
- [AZ-900](https://learn.microsoft.com/en-us/certifications/exams/az-900)
- [AZ-104](https://learn.microsoft.com/en-us/credentials/certifications/azure-administrator/)
- [CompTIA Security+](https://www.comptia.org/certifications/security)
- [Terraform Associate](https://developer.hashicorp.com/certifications/terraform-associate)
- [AWS Solutions Architect Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
- [AWS SAA-C03 exam guide](https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03.html)

This roadmap is educational, not a guarantee of employment or exam success. This repository is not endorsed by the certification vendors.
