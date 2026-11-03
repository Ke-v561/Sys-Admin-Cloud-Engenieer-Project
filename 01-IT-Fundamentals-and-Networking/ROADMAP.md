# Roadmap 01 — IT Fundamentals & Networking

**Outcome:** Collect system/network evidence and troubleshoot basic connectivity using repeatable tests rather than guesses.

## Project 01 — Windows System Inventory
**Objective:** Identify Windows version, CPU, RAM, storage, and current resource use.
1. Open Task Manager (`Ctrl+Shift+Esc`) → Performance → CPU; record CPU model.
2. Select Memory; record installed RAM and current usage.
3. Select primary disk; record type/capacity if shown.
4. Open Settings → System → Storage; record total and available storage.
5. Press `Win+R`, run `winver`, and record edition/version.
6. In PowerShell, run `Get-ComputerInfo | Select-Object CsName, WindowsProductName, WindowsVersion, OsBuildNumber` if available.
7. Compare the results and note fields that are unavailable or differ.
**Deliverable:** Sanitized `pc-inventory.md`.
**Pass criteria:** CPU, RAM, storage, and Windows version recorded; capacity vs. usage explained; private details redacted.

## Project 02 — Network Configuration Discovery
**Objective:** Identify the active adapter's IP configuration.
1. Open Command Prompt or PowerShell and run `ipconfig`.
2. Identify the connected Wi-Fi/Ethernet adapter.
3. Run `ipconfig /all`; locate IPv4 address, subnet mask, default gateway, DHCP status, and DNS servers.
4. Run `Get-NetIPConfiguration` and compare the active adapter.
5. Explain what each field does in your own words.
6. Redact MAC addresses, public IPs, SSID, and identifying details before publishing.
**Deliverable:** Sanitized `network-inventory.md`.
**Pass criteria:** Correct active adapter identified and the role of IP, mask, gateway, DHCP, and DNS explained.

## Project 03 — Connectivity & DNS Troubleshooting
**Objective:** Separate basic local-stack tests, reachability tests, and DNS tests.
1. Run `ping 127.0.0.1`; record result. ICMP may be restricted in some environments.
2. If a gateway exists, run `ping <gateway-address>`. A timeout alone does not prove the gateway is down.
3. Run `nslookup example.com`.
4. Run `nslookup example.invalid`; `.invalid` is reserved for invalid names, so resolution should fail.
5. Optionally run `tracert example.com`; some hops may not respond.
6. Create a table of test, result, what it suggests, and limitations.
**Deliverable:** `connectivity-case-study.md`.
**Pass criteria:** At least four tests documented; DNS distinguished from connectivity; no diagnosis based on one test alone.

## Project 04 — Troubleshooting Case Study
Use a safe, reversible issue such as the misspelled hostname above. Record symptom, test, evidence, diagnosis, action, and validation.
- [ ] All projects completed
- [ ] Reports committed without sensitive details
- [ ] Can explain the tests and their limitations
