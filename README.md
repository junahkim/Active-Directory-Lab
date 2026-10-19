# Active-Directory-Lab
A virtualized enterprise IT environment built using Windows Server 2025, Windows 11 Enterprise, and VirtualBox to simulate Active Directory administration, Group Policy management, user provisioning, and real-world IT help desk troubleshooting.

<h1>Tools/Technologies</h1>

- Oracle VirtualBox: virtualization platform for lab environment

- Windows Server 2025: domain controller and server administration

- Windows 11 Enterprise: simulated employee workstation

- Active Directory Domain Services: centralized user and computer management

- Group Policy Management: Configuration and enforcement of organizational policies

- DNS

- Powershell

<h1>Project Implementation</h1>

<h2>Virtual Environment Setup</h2>

- Windows Server 2025/Windows 11 Enterprise VM

- configure VM resources and connectivity

- install both OS and confirm connections

Host-only network configuration:
<img width="1436" height="851" alt="image" src="https://github.com/user-attachments/assets/9ec38edd-d031-4cb0-807e-bfefca8f2955" />

DC01 Adapter 1 configuration:

<img width="749" height="472" alt="image" src="https://github.com/user-attachments/assets/72d8db94-e079-4318-bbe4-f887a42afed6" />

DC01 Static IP configuration:

<img width="763" height="561" alt="image" src="https://github.com/user-attachments/assets/08de875b-8678-46a6-b92c-02af8e4581fc" />

Network connectivity:

<img width="535" height="254" alt="image" src="https://github.com/user-attachments/assets/597dc538-4513-495b-92ce-11dc397fabe5" />

<h2>Active Directory configuration</h2>

- install Active Directory Domain Services (AD DS)

- promote Windows Server to a domain controller

- Configure the domain and DNS

- Join the Windows 11 workstation to the domain

AD configuration:

<img width="1003" height="114" alt="image" src="https://github.com/user-attachments/assets/e0083155-4d39-4706-a3b8-613122576188" />

Domain Controller verification:

<img width="1024" height="194" alt="image" src="https://github.com/user-attachments/assets/2b2b9608-ad52-4470-804d-8e119ebeffd3" />

DNS verification:

<img width="1026" height="441" alt="image" src="https://github.com/user-attachments/assets/486db973-347e-4eb5-a8cb-0c4e0c772f68" />

AD Console:

<img width="767" height="536" alt="image" src="https://github.com/user-attachments/assets/d0236167-7c02-4b40-9611-db9a71f90b4a" />

