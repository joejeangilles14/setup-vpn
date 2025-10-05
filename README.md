<p align="center">
<img src="https://github.com/user-attachments/assets/d21c4c64-9498-4827-8d99-77d73116a69a" />
</p>

<h1>VPN Setup and Usage with Proton VPN</h1>
This tutorial outlines the prerequisites, installation and usage of the virtual private network Proton VPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Public Internet

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure Virtual Machine Windows 10, 4 vCPUs

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/e7bbd916-aaab-4319-ba99-b71104f8a810" />
</p>
<p>
Start by creating a virtual machine using Microsoft Azure.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/453a8391-73ac-4bd9-92b3-734f5498693e" />

</p>
<p>
Rename resource group to vpn-test, virtual machine renamed to myVm, and set region to East US (happens to be the only one available for the East coast).
<br />

<p>
<img src="https://github.com/user-attachments/assets/bd2ddfae-4046-41f9-a90b-b7931b542b4e" />
</p>
<p>
Select applicable region for VM size and select Windows 10 Pro version 22H2 x64 Gen2 as the image. Create login, confirm licensing, and click next until you reach review + create.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5cf8b52f-ff83-4ff4-9946-b1f7c6f05cc3" />
</p>
<p>
Review to confirm and click create.
</p>

<p>
<img src="https://github.com/user-attachments/assets/d95163e7-6162-4617-814b-37b323324aec" />
</p>
<p>
After deployment, return to Virtual Machines, copy and paste public IP address to Remote Desktop and login.
</p>
