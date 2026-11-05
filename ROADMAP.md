# Roadmap and dependencies

```text
IT Support Specialist + existing AD DS lab
        |
        v
00 - Reset/rebuild the lab and document a known-good baseline
        |
        v
01 - AZ-900 cloud/Azure fundamentals (exam optional)
        |
        v
02 - Mission-critical networking, Windows Server, AD DS, DNS/DHCP, PowerShell
        |
        v
03 - CompTIA Security+ SY0-701
        |
        v
04 - AZ-104 Azure Administrator Associate
        |
        v
05 - Terraform Associate 004
        |
        v
Cloud engineering portfolio: secure, deploy, automate, monitor, recover
        |
        +---- 06 - AWS SAA-C03 (optional multi-cloud extension)
```

## Why this order?
- Phase 00 removes unknown configuration and creates repeatable evidence.
- AZ-900 teaches cloud vocabulary and Azure service families; it is optional because it is not a prerequisite for AZ-104.
- Phase 02 builds the operating-system, networking, server, virtualization, identity, and scripting knowledge expected of Azure administrators.
- Security+ provides a broad security baseline before managing cloud infrastructure.
- AZ-104 is the primary role-based Azure administration credential.
- Terraform teaches repeatable infrastructure provisioning and change control.
- AWS SAA broadens architecture knowledge after the learner has a cloud foundation; it is not required for Azure-focused roles.

## Exit gates
| Phase | Exit gate |
|---|---|
| 00 | Rebuilt domain/client, documented topology, DNS verification, backup/recovery notes |
| 01 | AZ-900 passed if chosen; otherwise learning objectives and practice assessment complete |
| 02 | Independently troubleshoot DNS, domain join, AD, GPO, networking, and PowerShell tasks |
| 03 | Security+ passed and security controls demonstrated in lab documentation |
| 04 | AZ-104 passed and Azure admin project documented |
| 05 | Terraform Associate passed and infrastructure deployed from version-controlled code |
| 06 | AWS SAA passed and AWS architecture project documented (optional) |

After Phase 02, begin targeting junior systems/infrastructure responsibilities. After Phase 04, target Azure administrator, cloud operations, and appropriately scoped junior cloud engineering roles. Do not wait for every optional credential before applying.
