# Phase 7 — Cloud Operations, Incident Response, and Recovery

**Outcome:** Demonstrate operational thinking beyond deploying resources.

## Project 7.1 — Incident simulation

Use your Azure lab to simulate these failures independently:
1. A permission assignment prevents a user from accessing a resource.
2. A network security rule blocks expected connectivity.
3. A VM is stopped or an application endpoint is unavailable.

For each incident:
- Record symptom, scope, and timestamp.
- Gather logs and configuration evidence.
- State a hypothesis.
- Test one hypothesis at a time.
- Apply the smallest safe correction.
- Verify service restoration.
- Document root cause and prevention.

## Project 7.2 — Backup and disaster recovery
1. Select one lab workload and its data.
2. Define recovery point objective (RPO) and recovery time objective (RTO).
3. Choose a suitable backup approach.
4. Review retention, access, and cost.
5. Perform a test restore if supported and safe.
6. Document results and limitations.

## Project 7.3 — Cost control
1. Inventory resources that may incur charges.
2. Review sizing and utilization.
3. Add tags and budgets/alerts where available.
4. Estimate expected cost before deployment.
5. Shut down/delete test resources.
6. Verify dependent resources are also removed.

## Acceptance criteria
- [ ] Three incident reports completed
- [ ] One recovery procedure tested or clearly documented with evidence
- [ ] RPO and RTO defined
- [ ] Cost-control checklist completed
- [ ] All temporary cloud resources reviewed
