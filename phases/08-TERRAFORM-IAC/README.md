# Phase 08 — Terraform and infrastructure as code

## Purpose
Make infrastructure repeatable and reviewable. Learn Terraform fundamentals and use it to deploy a small Azure environment; compare with Bicep.

## End goal
Publish a sanitized Terraform project that can deploy and destroy a small Azure environment from documented inputs.

## Prerequisites
- Phase 06 complete; basic scripting and Azure administration.

## Certification
**Terraform Associate optional.** Optional credential after practical work. Official page: https://developer.hashicorp.com/certifications/infrastructure-automation .

## Estimated duration
**4–6 weeks** at 6–10 hours per week. Adjust based on demonstrated competence, not calendar pressure.

## Learning objectives and hands-on labs
1. Install Terraform and configure Azure authentication using a secure supported method; never hardcode secrets.
2. Write providers, resources, variables, outputs, locals, data sources, and modules.
3. Use fmt, validate, plan, apply, and destroy; explain each stage.
4. Use remote state only after understanding state security and access controls; never commit state.
5. Add validation, naming, tags, and environment variables; separate dev/test configuration.
6. Deploy a small Azure network and compute/storage resources; destroy and recreate cleanly.
7. Compare Terraform and Bicep: portability, ecosystem, state, Azure-native features, and team workflows.
8. Study the current Terraform Associate exam objectives if pursuing the credential.

## Final project
Publish a sanitized Terraform project that can deploy and destroy a small Azure environment from documented inputs.

## Completion criteria
- [ ] Can read a plan and predict the changes before apply.
- [ ] Can use variables/modules and explain state/locking/secrets.
- [ ] Can recover from a failed apply and avoid destructive drift.
- [ ] Can deploy and destroy the project reliably.
- [ ] Terraform Associate is optional; check current exam version and pricing.

## Cost planning
- Exam fees are listed as planning estimates in the repository root; verify official checkout pricing.
- Cloud usage can incur charges. Set budgets/alerts and delete resources after each exercise.

## Official references
- Microsoft Learn: https://learn.microsoft.com/training/
- Microsoft technical documentation: https://learn.microsoft.com/docs/
- Use the current provider exam guide where a certification is listed; versions and objective weights can change.
