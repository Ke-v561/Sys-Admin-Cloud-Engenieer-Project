# Safe Lab Practices
- Use test identities and synthetic data.
- Never commit passwords, tokens, private keys, certificates, connection strings, or Terraform state.
- Use a dedicated test subscription/account where possible.
- Set budgets/alerts; understand alerts may not stop spending.
- Prefer small VM sizes and short lab windows.
- Delete resources after labs and check for leftovers.
- Do not expose RDP/SSH or domain controllers directly to the public internet.
- Snapshot/backup before destructive changes.
- Sanitize screenshots, logs, hostnames, public IPs, and email addresses.
