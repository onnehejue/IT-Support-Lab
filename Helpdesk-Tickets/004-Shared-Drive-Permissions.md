# 004 — Configure HR shared-folder access and mapped drive

- **Type:** Retrospective lab access request.
- **Account/device:** Sarah Williams on `NEXORA-PC01`.
- **Priority:** Normal (illustrative).
- **Status:** Completed — Sarah's access and mapped drive confirmed.
- **SLA:** Not measured; timings not recorded.

## Task and actions

Shared `C:\CompanyShares\HR` on `NEXORA-DC01` as `\\NEXORA-DC01\HR`. Added the Active Directory `HR-Users` group to the folder's security permissions and allowed **Modify**. As Sarah, opened the share, created an empty test file and mapped the share to drive `H:`.

## Resolution and verification

The recorded lab confirms Sarah could open the share and create a file and that the mapped drive was completed. Full Control was not the permission selected for `HR-Users`.

The earlier record mixes the Daniel/Finance denied-access test with simulated images; that negative test and complete exclusion of other users are not asserted as verified.

## Screenshot process evidence

- [Drive mapping and resulting HR test file](../Active-Directory/05-Shared-Drive.md)
