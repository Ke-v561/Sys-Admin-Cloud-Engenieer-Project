# Phase 2 — Windows Systems Administration

**Outcome:** Build and operate a small isolated Windows domain.

## Project 2.1 — Domain controller

1. Create a Windows Server VM using a supported evaluation or licensed image.
2. Configure a static lab IP, hostname, and DNS settings.
3. Install Active Directory Domain Services.
4. Promote the server to a domain controller.
5. Create an isolated lab domain such as `ad.kevexelabs.test`.
6. Verify DNS and domain controller health.

## Project 2.2 — Users, groups, and OUs

1. Create OUs for Employees, IT, Servers, Workstations, and Disabled Accounts.
2. Create fictional users.
3. Create security groups such as `Lab-Helpdesk`, `Lab-IT-Admins`, and `Lab-Employees`.
4. Assign access through groups using least privilege.
5. Disable a test account and verify expected access behavior.

## Project 2.3 — Join a Windows client

1. Configure the client to use the lab DNS server.
2. Join it to the lab domain.
3. Sign in with a domain user.
4. Verify authentication and name resolution.
5. Test what happens when the domain controller is unreachable.

## Project 2.4 — Group Policy

1. Create a user or workstation policy.
2. Link it to the intended OU.
3. Run `gpupdate /force`.
4. Verify with `gpresult /r`.
5. Create a second policy and confirm scope/filtering behavior.

## Useful commands
```powershell
ipconfig /all
nslookup ad.kevexelabs.test
whoami
gpupdate /force
gpresult /r
Get-ADUser -Filter *
Get-ADGroup -Filter *
```

## Troubleshooting challenges
- Wrong DNS server on client.
- User missing required group membership.
- GPO linked to wrong OU or not applying.
- Time or connectivity issue affecting domain authentication.

## Acceptance criteria
- [ ] Domain controller healthy
- [ ] Client joined to domain
- [ ] Users, groups, and OUs created
- [ ] Two GPOs tested
- [ ] Three troubleshooting scenarios documented
- [ ] Lab report committed

Use fictional identities only. Do not connect this practice domain to employer systems.
