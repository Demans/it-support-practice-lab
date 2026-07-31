# KB-003 — DNS troubleshooting

## Goal
Determine whether the failure is connectivity, name resolution, client configuration, or a DNS service issue.

## Workflow
1. Define scope: one name, one device, one network, or many users.
2. Confirm basic connectivity to the gateway and a known lab IP.
3. Check the assigned fictional DNS servers.
4. Compare lookups against each lab DNS server.
5. Flush only the test client cache when appropriate.
6. Record timestamps and sanitized error output.
7. Escalate service-side failures with reproduction steps and impact.

## Useful lab commands
- `ipconfig /all`
- `ping`
- `nslookup`
- `Resolve-DnsName`

Never publish real internal hostnames, IP plans, VPN details, or unsanitized command output.
