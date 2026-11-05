# Safe lab practices

- Isolate lab networks from production and public networks.
- Do not port-forward domain services or management protocols.
- Use private DNS names and synthetic accounts.
- Keep a known-good admin account and documented recovery path.
- Snapshot before schema, domain, firewall, storage, or identity changes.
- Test restore procedures; a backup that has never been restored is unproven.
- Use least privilege and separate daily-use and administrative accounts.
- Store secrets in a local secret manager; use `.env` files only when excluded from Git.
- For cloud labs, use a dedicated subscription/resource group, budgets, alerts, tags, and cleanup checklist.
- Sanitize screenshots and logs before publishing.
