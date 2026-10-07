# Build the Windows domain lab

The sequence shows preparation, AD DS installation and the resulting domain. Initial VirtualBox OS labels describe the VM profile; the later Server Manager screen identifies Windows Server 2022.

## 1. Prepare the Windows 11 VM

VirtualBox shows the client VM resources and installation media; its adapter was initially NAT.

![Prepare the Windows 11 VM](screenshots/2026-10-03-145439.png)

## 2. Prepare the server VM

The server VM is configured with its disk and installation media.

![Prepare the server VM](screenshots/2026-10-03-152744.png)

## 3. Set the server internal network

The server adapter is configured for the internal network NEXORA-LAN.

![Set the server internal network](screenshots/2026-10-03-162744.png)

## 4. Set the client internal network

The client uses the same NEXORA-LAN internal network.

![Set the client internal network](screenshots/2026-10-03-162805.png)

## 5. Open Server Manager

The installed server reaches the Server Manager dashboard.

![Open Server Manager](screenshots/2026-10-03-164029.png)

## 6. Verify the server name and operating system

Local Server identifies NEXORA-DC01 and Windows Server 2022 Datacenter Evaluation.

![Verify the server name and operating system](screenshots/2026-10-03-214045.png)

## 7. Install Active Directory Domain Services

The role installation succeeded. This screen still requires promotion to a domain controller.

![Install Active Directory Domain Services](screenshots/2026-10-03-220536.png)

## 8. Verify the resulting domain

Active Directory Users and Computers shows nexora.local after domain setup.

![Verify the resulting domain](screenshots/2026-10-03-222148.png)

## 9. Organise users and groups

Department OUs and the HR users/security group are visible.

![Organise users and groups](screenshots/2026-10-04-090456.png)

