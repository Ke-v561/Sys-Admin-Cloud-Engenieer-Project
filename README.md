# From IT Support Specialist to Cloud Engineer

A hands-on, certification-aligned learning path built around a small home lab. The goal is not to collect badges: it is to become able to build, secure, automate, troubleshoot, document, and explain real infrastructure.

## Starting point
- Current role: IT Support Specialist
- Existing lab: Windows Server domain controller and one Windows client joined to the domain
- Study pace: 6–10 hours per week
- Platform direction: Azure-first, with transferable foundations and an optional AWS extension
- Budget: moderate; use free learning resources and local virtualization wherever practical

## How to use this repository
1. Start with [ROADMAP.md](ROADMAP.md).
2. Complete phases in order. Each phase has its own `README.md`, labs, a project, and independent exit criteria.
3. Keep evidence in your own private lab notes. Publish sanitized reports, diagrams, scripts, and screenshots only.
4. Do not move on because a video is finished. Move on when you can perform the tasks without step-by-step instructions and explain the result.
5. Update [PROGRESS-TRACKER.md](PROGRESS-TRACKER.md) as you go.

## The path
1. Lab reset and baseline
2. Networking foundations
3. Windows Server and Active Directory
4. Systems administration
5. Cloud fundamentals (AZ-900 exam optional)
6. Security foundations (Security+ exam optional)
7. Azure administration (AZ-104)
8. Linux and containers
9. Terraform and infrastructure as code
10. Cloud engineering capstone
11. AWS extension (optional)

## Certification philosophy
AZ-104 is the primary certification target. AZ-900 is optional because the learning objectives can be covered without paying for the exam. CompTIA Security+ is optional; the security knowledge is not. Terraform Associate is a useful optional credential after hands-on IaC work. AWS Solutions Architect Associate is an optional second-cloud credential, not a prerequisite for the Azure-first route.

Exam prices, versions, and objectives change. Check the linked official exam page before booking. Budget figures in `CERTIFICATION-COSTS.md` are planning estimates, not a promise of checkout pricing.

## Safety and licensing
- Keep domain controllers and lab services on private networks; never expose AD DS, RDP, SMB, WinRM, or management interfaces directly to the internet.
- Use synthetic users and data. Do not use employer/customer information.
- Snapshot or back up before destructive labs.
- Check Windows Server evaluation terms and Windows client licensing before building VMs. Do not assume every image or feature is free.
- Never commit passwords, tokens, private keys, `.tfstate`, cloud credentials, or unredacted logs.

## Definition of job-ready progress
By the end of the capstone you should be able to:
- Explain core network, identity, compute, storage, and security concepts.
- Administer a small Windows domain and troubleshoot common failures.
- Administer Windows and Linux systems using repeatable procedures and PowerShell/shell.
- Deploy and operate Azure resources with RBAC, networking, monitoring, backup, and cost controls.
- Build infrastructure from code using Terraform and Azure-native Bicep.
- Diagnose an outage from symptoms, logs, metrics, and configuration.
- Present architecture, trade-offs, security controls, runbooks, and evidence clearly.

This roadmap cannot guarantee employment. It is designed to produce demonstrable skills and a coherent portfolio that can support applications for junior cloud, cloud operations, systems, and infrastructure roles.
