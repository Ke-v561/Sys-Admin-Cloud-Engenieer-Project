# Phase 3 — PowerShell and IT Automation

**Outcome:** Read, modify, test, and explain scripts for routine administration.

## Topics
Variables, data types, arrays, objects, pipelines, conditions, loops, functions, error handling, CSV, logging, and basic script safety.

## Project 3.1 — System inventory script
Create `Get-LabSystemInfo.ps1` to report computer name, OS, uptime where available, memory, and IP configuration.

**Acceptance:** Runs on the lab endpoint and produces readable output.

## Project 3.2 — Connectivity diagnostic
Create `Test-LabConnectivity.ps1` to test:
- Ping/reachability where ICMP is allowed.
- DNS resolution for a supplied hostname.
- TCP reachability for a supplied host and port.

**Acceptance:** Reports each test clearly and handles invalid input.

## Project 3.3 — Active Directory report
Create `Export-LabUsers.ps1` to export lab users and selected properties to CSV.

**Acceptance:** Output is repeatable and contains only intended lab data.

## Project 3.4 — Add safe error handling
1. Validate inputs.
2. Use `try/catch` where appropriate.
3. Write meaningful error messages.
4. Add a timestamped log.
5. Test both successful and failed paths.

## Suggested repository layout
```text
03-powershell/
  scripts/
  sample-output/
  README.md
```

Never run untested scripts against production or employer systems. Start with read-only reporting before account-changing automation.
