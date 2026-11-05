# Safe lab practices

- Keep lab networks isolated from production and the public internet.
- Never expose AD DS, DNS, DHCP, SMB, RDP, WinRM, or hypervisor management directly to the internet.
- Use synthetic accounts/data and a known-good recovery admin.
- Snapshot before identity, firewall, storage, or domain changes.
- Test restores; an untested backup is unproven.
- Use least privilege and separate daily/admin accounts.
- Never commit credentials, `.env`, keys, tokens, Terraform state, or unredacted logs.
- For cloud labs, use dedicated resource groups, budgets, alerts, tags, and cleanup.
- Redact home IPs, tenant IDs, and personal details from screenshots.
