# Networking and DNS

## Completed checks

The lab client used static IPv4 `192.168.10.20` with DNS `192.168.10.10` on the internal VirtualBox network. The user chose to perform the network checks manually after earlier simulated images had been discussed.

- Reviewed IP configuration using `ipconfig`.
- Tested `ping 192.168.10.10`; the user reported replies.
- Tested the domain-controller hostname; the user reported it worked.
- Ran `nslookup nexora.local`; completion was reported and the conversation recorded successful DNS resolution.

These results establish lab connectivity and name resolution at that point. They do not prove external internet access or permanent resolution of the later GroupPolicy event.

See [ticket 003](../Helpdesk-Tickets/003-Network-DNS-Checks.md).

## Evidence checklist

Locate the genuine manually captured `11-Network-Troubleshooting-Verification.png`. Generated DNS/terminal screenshots are excluded. No screenshot is attached in this version.
