# Roadmap 03 — PowerShell & IT Automation

**Outcome:** Write readable, safe scripts that collect system information, validate input, handle errors, and create reports. Use only systems you own or are authorized to administer.

## Project 01 — PowerShell Orientation
1. Open PowerShell and run `$PSVersionTable`.
2. Run `Get-Command Get-Process`.
3. Run `Get-Help Get-Process -Examples` if help is available.
4. Run `Get-Process | Select-Object -First 5 Name, Id, CPU`.
5. Run `Get-Process | Get-Member` and explain object properties.
6. Save three commands and their explanations in `powershell-notebook.md`.
**Pass:** Can explain command discovery, objects, and the pipeline.

## Project 02 — System Information Collector
1. Create `Get-LabInventory.ps1`.
2. Collect computer name, Windows version, disk free space, and basic system details using supported cmdlets.
3. Add comments explaining each section.
4. Run it in a normal PowerShell session and capture sample output.
5. Redact host/user details before publishing.
**Pass:** Script runs without errors and outputs readable information.

## Project 03 — Error Handling & Logging
1. Add parameter support or a clearly defined output path.
2. Validate input and handle invalid paths.
3. Use `try/catch` where it meaningfully handles an error.
4. Write a timestamped log.
5. Test one normal case and two failure cases.
**Pass:** Errors are understandable and recorded without exposing secrets.

## Project 04 — CSV Reporting
1. Create a small fictional CSV with test data.
2. Import it with `Import-Csv`.
3. Validate required fields before processing.
4. Start in dry-run mode; do not modify real accounts or systems.
5. Export a summary using `Export-Csv`.
**Pass:** Input, output, and test cases are included.

## Project 05 — Help Desk Automation Capstone
Combine inventory, validation, logging, and CSV reporting in one tool. Include a README, usage examples, known limitations, and a test plan.
- [ ] Script is commented and repeatable
- [ ] Normal and failure cases tested
- [ ] No secrets or personal information committed
