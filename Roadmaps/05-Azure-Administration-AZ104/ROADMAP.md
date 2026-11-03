# Roadmap 05 — Azure Administration / AZ-104

**Outcome:** Plan, deploy, secure, monitor, and clean up basic Azure resources. Azure resources can incur charges; every lab must have a pricing and cleanup gate.

## Project 01 — Cost & Governance Preflight (planning only)
1. Review the current AZ-104 study guide.
2. Inspect the portal only if you already have an eligible account; do not create resources yet.
3. Draft a naming/tagging standard and resource-group plan.
4. List intended resources, expected purpose, pricing source, and exact cleanup steps.
5. Identify available budget/alert features for your account type.
6. Do not proceed until costs and deletion steps are understood.
**Deliverable:** `azure-lab-preflight.md`.

## Project 02 — Identity & RBAC
1. Learn principal, role, and scope.
2. Use a sandbox or training environment if available.
3. Build a role/scope matrix for a fictional team.
4. Explain least privilege and why tenant-wide admin permissions should not be used casually.
5. Do not change production/tenant-wide access for practice.
**Deliverable:** RBAC design matrix.

## Project 03 — Storage
1. Review storage options and access controls.
2. Check current pricing and eligibility before creating anything.
3. If a sandbox is available, create the smallest appropriate test resource.
4. Test authorized access and document the settings.
5. Delete the resource and verify cleanup.
**Deliverable:** Configuration, access test, and cleanup record.

## Project 04 — Virtual Network & VM
1. Draw the VNet/subnet and VM design before deploying.
2. Review pricing and secure access methods.
3. Avoid exposing remote management ports broadly to the internet.
4. Deploy only in a suitable sandbox/subscription after reviewing costs.
5. Test connectivity, record results, then stop/delete resources as planned.
**Deliverable:** Diagram, rule rationale, tests, cleanup evidence.

## Project 05 — Monitoring & Recovery
1. Identify available metrics, activity logs, alerts, and recovery options.
2. Distinguish a configured backup from a successfully tested recovery.
3. Write a recovery test plan and monitoring worksheet.
**Deliverable:** Monitoring and recovery report.

## Project 06 — Integrated Capstone
Plan, deploy, secure, monitor, document, and clean up a small environment using current AZ-104 objectives.
**Final milestone:** AZ-104. Verify the current Microsoft study guide before booking. A budget alert is not necessarily a hard spending cap.
