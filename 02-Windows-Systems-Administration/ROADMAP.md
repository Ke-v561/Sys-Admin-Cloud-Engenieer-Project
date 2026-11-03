# Roadmap 02 — Windows Systems Administration

**Outcome:** Build a small isolated Windows Server practice domain and demonstrate identity, groups, policy, and troubleshooting. Licensing and features vary; use legitimate installation media and an eligible license/evaluation.

## Project 01 — Design the Lab Before Installing
1. Record host OS, CPU, RAM, free disk space, and whether virtualization is enabled (Task Manager → Performance → CPU).
2. Choose one hypervisor available to you; do not install a second one blindly.
3. Identify a legitimate Windows Server evaluation/licensing path and client OS license.
4. Plan one Server VM and one client VM; estimate vCPU, RAM, and disk needs.
5. Draw an isolated virtual network. Do not expose a domain controller to the internet.
6. Write a rollback plan using snapshots/checkpoints or backups and a deletion plan.
**Deliverable:** `lab-design.md`. **Pass:** host capacity, licensing, diagram, isolation, and rollback plan documented before installing.

## Project 02 — Deploy the Lab
1. Create the server VM and client VM in your chosen hypervisor.
2. Install from legitimate media and record OS versions.
3. Use an isolated virtual network; record each VM's network settings.
4. Test basic connectivity only within the lab.
5. Take a clean snapshot/checkpoint if supported.
**Deliverable:** VM inventory, network diagram, and connectivity evidence.

## Project 03 — Active Directory Domain Services
1. Follow current Microsoft documentation to add AD DS to the server VM.
2. Promote the server to a domain controller using a lab-only domain name.
3. Configure the client to use the lab DNS server.
4. Join the client to the lab domain.
5. Verify domain membership and record errors if any.
**Deliverable:** Domain diagram and sanitized verification notes.

## Project 04 — Users, Groups & Least Privilege
1. Create test OUs for a fictional department.
2. Create two test users and two security groups.
3. Add users to appropriate groups rather than assigning permissions individually.
4. Test access to a harmless lab resource.
5. Record intended vs. actual access.
**Deliverable:** Account/group matrix and access test.

## Project 05 — Group Policy & Troubleshooting
1. Create a harmless GPO for a test OU.
2. Link it to the correct OU and place a test account/computer in scope.
3. Run `gpupdate /force` on the client.
4. Run `gpresult /r` or `gpresult /h gp-report.html` and inspect applied policies.
5. If it fails, check OU placement, link, security filtering, replication/DNS as applicable, and policy results.
**Deliverable:** GPO report and a troubleshooting case.

- [ ] Lab isolated and documented
- [ ] Domain join verified
- [ ] Users/groups tested
- [ ] GPO applied and verified
- [ ] Troubleshooting documented

**Certification note:** Do not assume an older Windows Server exam is current. Check Microsoft’s current credentials and target job postings before selecting a certification.
