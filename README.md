# DC-AD DS-DHCP-DNS 

## Setting up the environment
+ Installed and configured VirtualBox, Windows Server 2019, Windows 10 clients, and local network infrastructure.
+ Configured server names, TCP/IP, domain controller, DHCP scopes, and DNS records.

## Secondary Domain Controller Deployment

+ Configured static IP on a second server and set primary DC’s IP as DNS.
+ Installed AD DS role and promoted the server as a domain controller in the existing domain, including DNS configuration, DSRM setup, and replication from the host DC.

## Domain Controller & DNS Verification

+ Verified the new DC in Active Directory Users and Computers and confirmed DNS zone replication.
+ Updated DNS settings on both servers to use local DNS.

## Replication & GPO Management

+ Used AD Sites and Services to verify NTDS settings and manually triggered replication.
+ Tested replication by creating users and Group Policy Objects (GPOs). Created, linked, and tested GPOs, validating file shares and access permissions.

## Client Machine Integration
+	Added Windows 10 clients to the domain, configuring networking, OS setup, and user accounts to simulate real-world environment.
