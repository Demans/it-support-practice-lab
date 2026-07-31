# INC-003 — Printer displayed as offline

- Support level: L1
- Status: Resolved
- Priority: P3
- Environment: Fictional office network printer

## Report
One simulated workstation could not print while other fictional users could.

## Checks performed
1. Confirmed the issue was limited to one workstation.
2. Checked the print queue and removed a stuck fictional job.
3. Verified the correct printer was selected and not set to Use Printer Offline.
4. Restarted the Print Spooler in the lab.
5. Printed a fictional test page.

## Resolution
The stuck queue item was cleared and printing resumed.
