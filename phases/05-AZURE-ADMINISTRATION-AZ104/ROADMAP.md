# Phase 5 — Azure Administration (AZ-104)

**Outcome:** Deploy, configure, secure, monitor, and troubleshoot Azure resources.

## Official preparation
- Certification: https://learn.microsoft.com/credentials/certifications/azure-administrator/
- Study guide: https://learn.microsoft.com/credentials/certifications/resources/study-guides/az-104
- Microsoft Learn: https://learn.microsoft.com/training/

Always use the current exam study guide; objectives can change.

## Project 5.1 — Identity and governance
1. Create lab users and groups in Microsoft Entra ID where your tenant supports it.
2. Assign an appropriate Azure RBAC role at a limited scope.
3. Test access using a non-admin identity.
4. Inspect role assignments and correct an intentional permission error.

**Pass:** Explain why access succeeds or fails and demonstrate least privilege.

## Project 5.2 — Virtual networking
1. Create an Azure VNet and two subnets.
2. Configure an NSG with narrowly scoped rules.
3. Deploy a test VM into the intended subnet.
4. Test allowed and denied connectivity.
5. Use available diagnostic tools to isolate a failure.

**Pass:** Explain addressing, routing, NSG evaluation, and secure management access.

## Project 5.3 — Compute
1. Deploy a small Windows or Linux VM.
2. Select a cost-conscious size.
3. Configure secure management access.
4. Inspect metrics and VM configuration.
5. Stop/deallocate and remove resources when finished.

**Pass:** Deploy, connect, diagnose a connection failure, and clean up.

## Project 5.4 — Storage
1. Create a storage account.
2. Create a Blob container.
3. Upload and retrieve synthetic test data.
4. Review access controls, redundancy, and storage tiers.
5. Remove test data/resources when complete.

**Pass:** Explain how access is controlled and how cost/redundancy choices differ.

## Project 5.5 — Monitoring and recovery
1. Inspect VM metrics and logs.
2. Configure a suitable test alert where available.
3. Review backup options and pricing.
4. Test a restore only in a controlled lab.
5. Document recovery steps and limitations.

**Pass:** Identify a simulated issue and explain the evidence and recovery path.

## Project 5.6 — Repeatable deployment
Use Bicep, Azure CLI, or PowerShell to deploy a small, repeatable resource group and network/compute configuration.

**Pass:** Deploy, validate, make a controlled change, and remove resources cleanly.

## Cost and safety
- Check pricing before creating resources.
- Use small SKUs and short lab windows.
- Configure budgets/alerts where available; alerts are not guaranteed spending caps.
- Verify cleanup of VMs, disks, public IPs, snapshots, storage, and monitoring resources.

## AZ-104 acceptance
- [ ] Identity/governance lab
- [ ] Networking lab
- [ ] Compute lab
- [ ] Storage lab
- [ ] Monitoring/maintenance lab
- [ ] Repeatable deployment
- [ ] Current study guide reviewed
- [ ] Practice questions and weak areas reviewed
- [ ] AZ-104 exam completed
