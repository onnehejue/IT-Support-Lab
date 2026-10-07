# Join Windows 11 to the domain

The initial domain-controller discovery failure leads into DNS investigation, then a successful join and domain-user verification. The DNS investigation has its own detailed sequence.

## 1. Observe the failed join

The client could not contact an Active Directory domain controller for nexora.local.

![Observe the failed join](screenshots/2026-10-04-104146.png)

## 2. Confirm the successful join

The client receives Welcome to the nexora.local domain.

![Confirm the successful join](screenshots/2026-10-04-110754.png)

## 3. Verify user and workstation

whoami returns nexora\sarah.williams and hostname returns NEXORA-PC01.

![Verify user and workstation](screenshots/2026-10-04-111927.png)

