# Phase 1 — IT Fundamentals and Networking

**Outcome:** Diagnose common endpoint, IP, DNS, gateway, and connectivity problems.

## Topics to learn
- IPv4 addressing, subnet masks, CIDR, private/public IPs
- Default gateways and routing basics
- DNS records and name resolution
- DHCP leases and reservations
- TCP vs UDP, ports, and basic firewall behavior
- Windows networking tools

## Project 1.1 — Baseline a Windows client

1. Run `ipconfig /all`.
2. Identify IP, mask, gateway, DNS, DHCP server, and lease.
3. Run `route print`.
4. Run `nslookup example.com`.
5. Run `Test-NetConnection example.com -Port 443`.
6. Save sanitized output and explain each result.

## Project 1.2 — Troubleshoot controlled failures

In a lab client only:
1. Record baseline DNS and connectivity.
2. Change DNS to an intentionally incorrect lab value.
3. Test name resolution and record the exact error.
4. Restore correct DNS.
5. Repeat with an incorrect default gateway only if you can safely recover console access.
6. Explain the difference between DNS failure and routing failure.

## Expected results
- You can distinguish IP configuration, DNS, routing, and port reachability problems.
- You can describe the path from a client to a remote service.

## Acceptance criteria
- [ ] Baseline report complete
- [ ] DNS failure diagnosed and corrected
- [ ] TCP port test explained
- [ ] Troubleshooting report committed
