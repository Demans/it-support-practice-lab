# IT Support Practice Lab

A public portfolio lab for documenting **simulated** first- and second-level IT support work. It demonstrates ticket handling, troubleshooting, escalation, user communication, and knowledge-base writing without using real customer or company data.

> All people, devices, systems, identifiers, logs, and error messages in this repository are fictional. Never add secrets, personal data, private screenshots, or real infrastructure details.

## Start here

1. Copy [the incident template](templates/incident-ticket.md).
2. Create a fictional case under `tickets/l1/`.
3. Record questions, evidence, actions, decisions, communication, and validation.
4. Use [the L2 handoff template](templates/l2-escalation-handoff.md) when the case exceeds L1 scope.
5. Turn repeatable fixes into a knowledge-base article.
6. Complete the privacy checklist before committing.

## Repository map

- `.github/ISSUE_TEMPLATE/` — GitHub ticket templates for L1 cases and L2 escalations
- `templates/` — reusable Markdown ticket and handoff templates
- `tickets/l1/` — first-level triage and common end-user fixes
- `tickets/l2/` — advanced investigation, root cause, and controlled remediation
- `knowledge-base/` — Windows, hardware, networking, Microsoft 365, and security articles
- `assets/screenshots/` — rules for mock or sanitized visual evidence
- `PRIVACY.md` — mandatory data-handling rules

## Example cases

### L1

- [INC-001 — Windows laptop running slowly](tickets/l1/INC-001-slow-windows-laptop.md)
- [INC-002 — External monitor not detected](tickets/l1/INC-002-external-monitor-not-detected.md)
- [INC-003 — Printer displayed as offline](tickets/l1/INC-003-printer-offline.md)

### L2

- [INC-101 — Intermittent DNS resolution](tickets/l2/INC-101-intermittent-dns-resolution.md)
- [INC-102 — Repeated account lockout](tickets/l2/INC-102-repeated-account-lockout.md)

## Suggested ticket workflow

`New → Assigned → In progress → Pending user/vendor → Resolved → Closed`

For every case, show clear scope and priority, reproducible troubleshooting, what each check proved, user-facing updates, escalation criteria, resolution validation, and a final privacy check.

## Portfolio note

This lab demonstrates process and communication, not access to a real production environment. Describe every example honestly as a simulation or home lab.
