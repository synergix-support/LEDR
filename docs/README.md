# **SYNERGIX LEDR**


## Overview

The software SYNERGIX LEDR offers significant value compared to its predecessor SYNERGIX SEVA and competitors' products from CyberArk, Dilinea and others.

[<span style="color:yellow;font-weight:bold;;">Privilege Access Management / Admin On Demand</span>](/products/ledr/configuration/feature/admin-on-demand) feature addresses Privileged Access Management requirements by offering Just-In-Time Administration capabilities, allowing end users to run approved programs with elevated privileges. It offers practical and economical alternative to CyberArk EPM, [Admin On Request](https://www.adminbyrequest.com/) and other PAM solutions.

[<span style="color:yellow;font-weight:bold;;">Bastion Remote Desktop / SSH Web Access Gateway</span>](/products/ledr/configuration/feature/admin-on-demand) provides secure and seamless RDP/SSH access to Windows and SSH access to Linux and OSX Systems, directly from a desktop browser or mobile device. It eliminates vulnerability in Internet facing public IP addresses for remote access, by offering secure connectivity within your virtual network. 

Unlike [Azure Bastion](https://www.cloudthat.com/resources/blog/enhancing-secure-remote-access-with-azure-bastion), the software's Bastion feature offers superior capabilities and without additional cost.  It extends its capabilities to On Premises or Cloud hosted Windows and Linux devices. [<span style="color:yellow;font-weight:bold;;">Remote Desktop Protocol Port Rotation</span>](/products/ledr/configuration/feature/remote-desktop-protocol-port-rotation) and [<span style="color:yellow;font-weight:bold;;">SSHD Port Rotation</span>](/products/ledr/configuration/feature/openssh-server-port-rotation) add another security layer, by discouraging use of the static and well known 3389/tcp or 22/tcp network communication ports.

<span style="color:yellow;font-weight:bold;;">Session recording</span> capabilities fulfill auditing requirements.


[<span style="color:yellow;font-weight:bold;;">Universal LAPS</span>](/products/ledr/configuration/feature/universal-laps) features is Operating System agnostic and is one of the many key selling [features](/home#universal-laps-features) in the product. With Privilege Access Management / Admin on Demand feature, it offers an alternative to [CyberArk EPM](https://www.cyberark.com/products/endpoint-privilege-manager/)

The software improves security posture of endpoints, by rotating the logon names and passwords/pass phrases of all local accounts, existing or new accounts, including MS SQL Server sa account password!  Password may be retrieved from the dashboard by authorized users only.

SYNERGIX LEDR is Operating System agnostic and works on 

- MacOS
- Windows and
- Linux
> RedHat, Oracle Linux, CentOS, Debian, Ubuntu, Fedora, OpenSUSE, and more.
> Linux based appliances such as Tenable Nessus Vulnerability Scanner, OpenVPN and more.

---

The software supports ...
- Active Directory joined computers
- Entra ID joined computers and 
- Workgroup computers (Windows, macOS, Linux and Linux based appliances)
- Devices hosted in DMZ, AWS, GCP and in other Cloud Service Providers

## Privacy First
> The software is a Cloud App hosted in customer's Azure Tenant.

The Cloud App is hosted in customer's Azure Tenant, and the secrets are stored securely in customer's Azure Key vault, with exclusive access to the customer associates only.  Error reporting data, if any, is forwarded to Log Analytics Workspace in the customer's Azure Tenant.


## Universal LAPS Features
<br/>

| Features | Microsoft LAPS | SYNERGIX LEDR |   
| --- | --- | --- |
| Local Administrator Password Solution | ![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)   | ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |
| Backup Administrator Password Solution | ![not-available-48.png](/images/not-available-48.png)| ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |  
| Least Privilege User Password Solution | ![not-available-48.png](/images/not-available-48.png)| ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |
| Air-Gapped Systems. Password Rotation | ![not-available-48.png](/images/not-available-48.png)| ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |
| Logon Name Rotation | ![not-available-48.png](/images/not-available-48.png)| ![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |    
| Non-Compliant Local Users Password Solution | ![not-available-48.png](/images/not-available-48.png) | ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |    
| Chetak* Administrator Password Solution | ![not-available-48.png](/images/not-available-48.png) | ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |  
| Microsoft SQL sa Password Solution | ![not-available-48.png](/images/not-available-48.png) | ![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |  
| Remote Desktop Port Rotation | ![not-available-48.png](/images/not-available-48.png) | ![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |     
| SSHD Port Rotation | ![not-available-48.png](/images/not-available-48.png) |  ![icons8-apple-50.png](/images/icons8-apple-50.png)![icons8-linux-48.png](/images/icons8-linux-48.png)![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |  
| Autologon Account Password Solution | ![not-available-48.png](/images/not-available-48.png) | ![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |     

## Non-compliant Local Accounts
All local user accounts on Windows, Linux and macOS will have their passwords rotated, ensuring the security of the systems. Designated administrators may retrieve the password from the web dashboard to login with such accounts and decide to disable or delete all such local user accounts, for auditing and for operational risk management purposes.


## Microsoft SQL Server sa Password Rotation
When this feature is enabled and properly configured, it will rotate Microsoft SQL sa Account Password and store it in the vault.

|  Microsoft SQL Server | Windows OS | Linux   |  Comments |
| --- | --- | --- | --- | --- |
| Microsoft SQL Server 2022 | :white_check_mark:  | :x: | Linux support planned  |
| Microsoft SQL Server 2019 | :white_check_mark:  | :x: |   |
| Microsoft SQL Server 2017 | :white_check_mark:  | :x: |   |



### Password Encryption

|  | Microsoft LAPS | SYNERGIX LEDR |  
| --- | --- | --- | 
| Authorized Security Principal | One  | Agnostic |  

### Unauthorized Password Readers

|  | Microsoft LAPS | SYNERGIX LEDR |   
| --- | --- | --- | --- | --- |
| Device | :white_check_mark:  | :x: |   

Reference: 
[DSRM Password Support](https://learn.microsoft.com/en-us/windows-server/identity/laps/laps-concepts-overview#dsrm-password-support)

> When encrypted password history is enabled and it's time to rotate the password, **the managed device first reads the current version of the encrypted password from Windows Server Active Directory**. The current password is then added to the password history. Prior passwords in the history vault are deleted, when needed, to comply with the configured maximum history limitation.

### Authorized Password Readers
The software strictly follows Principle of Least Privileges.  High privileged accounts in Entra ID or in Active Directory Domain Services are not granted high privileges in SYNERGIX LEDR software.

|  | Microsoft LAPS | SYNERGIX LEDR |  
| --- | --- | --- | --- | --- |
| Global Administrator | :white_check_mark:  | :x: |  
| Cloud Device Administrator | :white_check_mark:  | :x: |  
| Intune Administrator | :white_check_mark:  | :x: |   

By default, Windows LAPS allows members of the Global Administrator, Cloud Device Administrator, and Intune Administrator roles to retrieve the clear-text password.  In contrast SYNERGIX LEDR requires proper assignment of Password Reader permission.


### Identity Provider Agnostic

|  | Microsoft LAPS | SYNERGIX LEDR |   
| --- | --- | --- | --- | --- |
| Identity Providers | ![entra-id-48.png](/images/entra-id-48.png) ![adds-48.png](/images/adds-48.png)  | ![entra-id-48.png](/images/entra-id-48.png) ![adds-48.png](/images/adds-48.png) ![workgroup-computer-48.png](/images/workgroup-computer-48.png) ![aws-48.png](/images/aws-48.png) ![google-48.png](/images/google-48.png)|   


### Windows Operating Systems
| Operating Systems | Microsoft LAPS | SYNERGIX LEDR |
| - | - | - |
| Windows 7.0 SP1 | :x:  | :white_check_mark: |
| Windows 8.0 | :x:  | :white_check_mark: |
| Windows 10 | :white_check_mark:  | :white_check_mark: |
| Windows 11 | :white_check_mark:  | :white_check_mark: |
| Windows Server 2008/R2 | :x:  | :white_check_mark: |
| Windows Server 2012/R2 | :white_check_mark:  | :white_check_mark: |
| Windows Server 2016 | :white_check_mark:  | :white_check_mark: |
| Windows Server 2019 | :white_check_mark:  | :white_check_mark: |
| Windows Server 2022 | :white_check_mark:  | :white_check_mark: |
| Windows Server 2025 | :white_check_mark:  | :white_check_mark: |


### Linux Distributions
| Operating Systems | Microsoft LAPS | SYNERGIX LEDR |
| - | - | - |
| CentOS | :x:  | :white_check_mark: |
| Debian | :x:  | :white_check_mark: |
| Fedora | :x:  | :white_check_mark: |
| Kali Linux | :x:  | :white_check_mark: |
| openSUSE | :x:  | :white_check_mark: |
| Oracle 9 | :x:  | :white_check_mark: |
| RedHat Enterprise Linux | :x:  | :white_check_mark: |
| Ubuntu Desktop | :x:  | :white_check_mark: |
| Ubuntu Server | :x:  | :white_check_mark: |
*The software should also work on all Linux Distributions that can run .NET Core 8.0*

### Apple macOS
| Operating Systems | Microsoft LAPS | SYNERGIX LEDR |
| --- | --- | --- |
| Catalina  | :x:  | :white_check_mark: |
| Big Sur  | :x:  | :white_check_mark: |
| Monterey  | :x:  | :white_check_mark: |
| Ventura | :x:  | :white_check_mark: |
| Sonoma | :x:  | :white_check_mark: |
| Sequoia | :x:  | :white_check_mark: |


### Appliances
| Operating Systems | Microsoft LAPS | SYNERGIX LEDR |
| --- | --- | --- |
| openVPN  | :x:  | :white_check_mark: |
| Bitnami Stacks  | :x:  | :white_check_mark: |
| Tenable Nessus Vulnerability Scanner  | :x:  | :white_check_mark: |

## Admin on Demand
When the feature is enabled, users are granted Just-In-Time Administration privileges and can launch selected applications with admin token.

## Remote Desktop Protocol (RDP) Port Rotation
When the feature is enabled, RDP port is randomly assigned a number in specified high range, such as 33389 to 43389, along with updating the Windows Firewall rule.  

New Windows Firewall rule is created but not enabled, denying the inbound connection on rotated port number until the configuration is updated to allow inbound network connection on the assigned RDP port.

For added benefit, consider implementation of Chetak*, a deception technique.

| Features | Microsoft LAPS | SYNERGIX LEDR |  
| --- | --- | --- |
| Remote Desktop Protocol Rotation | ![not-available-48.png](/images/not-available-48.png)| ![icons8-windows-11-48.png](/images/icons8-windows-11-48.png)    |

## Process Guard
When the feature is enabled, execution of Living of the Land Binaries (Lolbins) such as adfind.exe, msbuild.exe, csc.exe and others that are specified in the software configuration, by any non-system account, are challenged with a captcha prompt.

## SIEM Integration
When the feature is enabled, software forwards selected Security Events and Sysmon Events to customer's Azure Log Analytics Workspace, enabling Cyber Security Operations Analyst build detection rules.

### Security Events
Specific Windows Events, such as 4624 and others, are forwarded to Azure Log Analytics Workspace.

### Sysmon Events
All events configured in Sysmon configuration file, are forwarded to Azure Log Analytics Workspace.

### Detection Rules
- Users logging in from unowned devices
- DNS queries to search for malicious domains
- Processes launched from $Recycle.Bin
- Processes launched with high privileges
- PowerShell encoded commands
- PowerShell Download
- Sticky-key attack
- More ...

# Additional Features
## Service Monitoring
<br/>

## Inventory
<br/>

## RBAC
<br/>

## Open API
<br/>

## Auditing
<br/>

## References
For more information, visit https://www.synergix.com

(c) 2026 Synergix Labs.
Optaguard is a product brand of Synergix Labs

