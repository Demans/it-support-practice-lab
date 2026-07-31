# INC-101 — Intermittent DNS resolution

- Support level: L2
- Status: Resolved
- Priority: P2
- Environment: Fictional lab VLAN
- Scope: Multiple simulated endpoints

## Escalation reason
L1 confirmed network connectivity by IP address, but hostnames failed intermittently across multiple lab devices.

## Investigation
1. Compared name resolution against the primary and secondary fictional DNS servers.
2. Confirmed failures occurred only when queries reached the secondary server.
3. Reviewed sanitized service logs and found an outdated fictional forwarder.
4. Corrected the lab forwarder configuration after documenting rollback steps.
5. Cleared test caches and validated repeated lookups from several simulated clients.

## Resolution
Name resolution became stable after correcting the secondary lab DNS forwarder.

## Root cause
A fictional stale forwarder configuration on the secondary DNS server.
