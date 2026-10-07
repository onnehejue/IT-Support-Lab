# 003 — Workstation network and DNS verification

- **Type:** Retrospective lab troubleshooting record.
- **Device:** `NEXORA-PC01` on `nexora.local`.
- **Priority:** Normal (illustrative).
- **Status:** Completed — connectivity/name-resolution checks recorded.
- **SLA:** Not measured; timings not recorded.

## Task and investigation

Verified connectivity between the Windows 11 client and its domain controller on the internal VirtualBox network. Reviewed IP settings using `ipconfig`, tested the server IP (`192.168.10.10`) with `ping`, tested the `NEXORA-DC01` hostname, and ran `nslookup nexora.local`.

## Outcome

The user reported ping replies, working hostname connectivity and completion of the DNS lookup. The lab conversation recorded DNS resolution as working. No configuration change is attributed to this verification sequence.

External internet connectivity was not established: the internal network had no default gateway. Resolution of the later GroupPolicy Event 1054 is not claimed.

## Evidence

Original manual capture referenced: `11-Network-Troubleshooting-Verification.png` (not attached). Generated command-output images are excluded.
