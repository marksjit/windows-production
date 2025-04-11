# DC-AD DS-DHCP-DNS 

## Setting up the environment
+ Installed and setup VirtualBox, Windows Server 2019, Windows 10 clients, and local network.
+ Configured server name, TCP/IP settings, domain controller, DHCP scopes and DNS records.

## Adding a Second Domain Controller

+ Configured static IP on the second server and set the primary DC’s IP as its DNS.
+ Installed AD DS role, promoted the server to a domain controller in the existing domain using host DC credentials.
+ Ensured DNS role was selected, set DSRM password, and replicated from host DC. Server auto-restarted after promotion.

## Verifying Domain Controller and DNS Setup

+ Confirmed new DC presence in ADUC under Domain Controllers and verified DNS zones.
+ Updated DNS settings on both servers to point to their respective local DNS.

## Ensuring Proper Replication

+ Used AD Sites and Services to verify NTDS settings and manually triggered replication on both DCs.
+ Tested replication by creating new users and GPOs across the domain controllers.

## Deploying GPOs, testing out functionalities and effectivity
+	Created and linked Group Policy Objects in Active Directory.
+ Checked file shares and access management, making sure the correct user can access resources correctly.

## Adding machines that simulates real-world client computers
+	Added client machines to Windows Server 2019 domain.
+ Configured networking, client OS setup and user accounts.
