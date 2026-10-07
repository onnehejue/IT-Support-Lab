# 003 — Workstation network and DNS verification

- **Type:** Retrospective lab troubleshooting record.
- **Device:** `NEXORA-PC01` on `nexora.local`.
- **Priority:** Normal (illustrative).
- **Status:** Completed — connectivity/name-resolution checks recorded.
- **SLA:** Not measured; timings not recorded.

## Task and investigation

Verified connectivity between the Windows 11 client and its domain controller on the internal VirtualBox network. Reviewed IP settings using `ipconfig`, tested the server IP (`192.168.10.10`) with `ping`, tested the `NEXORA-DC01` hostname, and ran `nslookup nexora.local`.

## Outcome

The supplied screenshots show four ping replies with 0% loss by IP and hostname. The DNS lookup returns nexora.local at 192.168.10.10 after an initial timeout and Unknown server label; that warning remains part of the record. No configuration change is attributed to this verification sequence.

External internet connectivity was not established: the internal network had no default gateway. Resolution of the later GroupPolicy Event 1054 is not claimed.

## Screenshot process evidence

- [IP, ping and DNS verification](../Networking-DNS/02-Network-Verification.md)
- [Earlier discovery failure and investigation](../Networking-DNS/01-DNS-Investigation.md)
