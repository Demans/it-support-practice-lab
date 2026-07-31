# INC-102 — Repeated account lockout

- Support level: L2
- Status: Resolved
- Priority: P2
- Environment: Fictional identity lab
- Simulated account: training.user

## Escalation reason
The account locked again after an L1 password reset, indicating a cached credential or repeated authentication source.

## Investigation
1. Reviewed sanitized fictional lockout timestamps.
2. Correlated attempts with a simulated mobile mail profile.
3. Removed the obsolete saved credential from the lab profile.
4. Reset the fictional password once more.
5. Monitored the lab account through the test window.

## Resolution
No further lockouts occurred after the obsolete credential was removed.

## Safety note
Real authentication logs can contain usernames, addresses, device names, and infrastructure details. Redact them before documentation and never record passwords.
