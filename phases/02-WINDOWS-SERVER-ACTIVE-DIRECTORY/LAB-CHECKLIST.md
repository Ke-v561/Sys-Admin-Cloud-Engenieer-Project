# Active Directory lab checklist

- [ ] Build a clean Server VM on a private virtual switch.
- [ ] Set static IP, hostname, time source, and DNS configuration.
- [ ] Install AD DS and create a private test forest (for example, `corp.example.test`).
- [ ] Create OUs for Users, Workstations, Servers, and Groups.
- [ ] Create role-based security groups; assign permissions to groups, not individuals.
- [ ] Create test users and a separate admin account.
- [ ] Join a Windows client to the domain.
- [ ] Create and test at least three GPOs; record `gpresult` output.
- [ ] Configure DNS records and verify client registration/resolution.
- [ ] Troubleshoot a deliberately incorrect DNS setting and a GPO scope issue.
- [ ] Review account lockout and authentication events.
- [ ] Back up System State and document restore/recovery steps.
- [ ] Draw the domain, OU, group, DNS, and client relationship.
