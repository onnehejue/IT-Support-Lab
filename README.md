# Nexora IT Support Lab

A beginner IT support portfolio documenting hands-on practice in a virtual Windows domain and a Microsoft 365 lab tenant. Nexora is a lab scenario; this portfolio does not represent employment or production support experience.

## Lab environment

- Oracle VirtualBox with Windows Server 2022 and Windows 11.
- Domain: `nexora.local`; server: `NEXORA-DC01`; workstation: `NEXORA-PC01`.
- Internal lab network: server `192.168.10.10`, workstation `192.168.10.20`, mask `255.255.255.0`; client DNS points to the domain controller. No default gateway was configured for the internal network.
- Microsoft 365 test tenant with the Sarah Williams lab account.

## Explore the portfolio

| Area | Work documented |
| --- | --- |
| [Active Directory](Active-Directory/README.md) | Domain environment, user administration and shared-folder access |
| [Windows 11 Support](Windows-11-Support/README.md) | Storage cleanup and Event Viewer investigation |
| [Networking and DNS](Networking-DNS/README.md) | IP, reachability and DNS checks |
| [Microsoft 365 and Entra](Microsoft-365-Entra/README.md) | User/licence administration, password reset, sign-in blocking, groups and MFA |
| [Helpdesk Tickets](Helpdesk-Tickets/README.md) | Five concise retrospective records based on completed lab actions |

## Evidence and scope

These notes were reconstructed from the completed lab conversation. Screenshots are not included in this first version: earlier materials included both real captures and generated simulations, so none have been treated as verified screenshot evidence here. References to screenshot filenames are an evidence checklist, not links to files already present.

The ticket format demonstrates documentation skills. Priorities are illustrative, while customer reports, response times and SLA compliance are not claimed. Administrative confirmation is distinguished from end-user testing. Enabling per-user MFA does not establish successful enrolment, enforcement or an MFA sign-in test.

Shared mailbox administration, Teams/OneDrive troubleshooting, BitLocker, remote support and software installation/removal are not claimed as completed.
