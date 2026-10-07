# Disable and restore a domain account

This sequence shows a blocked Windows sign-in, the administrative recovery action, its confirmation and a subsequent domain-user session.

## 1. Observe the disabled-account sign-in

Windows reports that Sarah's account has been disabled.

![Observe the disabled-account sign-in](screenshots/2026-10-04-113058.png)

## 2. Select Enable Account

The administrator selects the Enable Account action in Active Directory Users and Computers.

![Select Enable Account](screenshots/2026-10-04-113535.png)

## 3. Verify administrative success

Active Directory confirms that Sarah Williams has been enabled.

![Verify administrative success](screenshots/2026-10-04-113559.png)

## 4. Verify the user session

After recovery, whoami returns nexora\sarah.williams.

![Verify the user session](screenshots/2026-10-04-113911.png)

