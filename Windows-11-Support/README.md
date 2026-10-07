# Windows 11 Support

## Storage cleanup

On `NEXORA-PC01`, investigated the Storage breakdown, reviewed temporary-file categories, completed cleanup and returned to Storage for verification. The conversation confirms completion but does not preserve a measured amount of space recovered. No numeric saving or production low-disk incident is claimed.

Original capture to locate: `12-Disk-Cleanup-Storage-Verification.png`.

## Event Viewer investigation

Opened Windows Logs > System and filtered Critical, Error and Warning events. Inspected a GroupPolicy error, Event ID **1054**, on `NEXORA-PC01.nexora.local`. The recorded message concerned obtaining the domain-controller name and DNS/name resolution.

This documents identifying and interpreting an event. A successful `gpupdate /force` or resolution of Event 1054 is not established by the available record and is not claimed.

Original capture to locate: `13-Event-Viewer-GroupPolicy-Error-1054.png`. No screenshot is attached in this version.
