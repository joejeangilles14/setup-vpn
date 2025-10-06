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
<img src="https://github.com/user-attachments/assets/3c876dc4-d1eb-456c-9da9-95b66efd5457" />
</p>
<p>
Rename resource group to vpn-test, virtual machine renamed to VPN-Test (or some form of similarity), and set region to East US (happens to be the only one available for the East coast currently).
<br />

<p>
<img src="https://github.com/user-attachments/assets/3994e8d5-7d06-4095-9460-0395db02f198" />
<img src="https://github.com/user-attachments/assets/91d4df7a-1b25-4318-9849-8ad303ae408c" />
</p>
<p>
Select applicable region for VM size and select Windows 10 Pro version 22H2 x64 Gen2 as the image. Create login, confirm licensing, and click next until you reach review + create.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/167bc071-6263-410e-a0fb-d777c340b942" />
</p>
<p>
Review to confirm and click create.
</p>

<p>
<img src="https://github.com/user-attachments/assets/609f7765-eaf4-41ef-9fdf-a99cae0496c8" />
<img src="https://github.com/user-attachments/assets/7ae548ea-b003-4543-bcd2-e3826799d48f" />
</p>
<p>
After deployment, return to Virtual Machines, copy and paste public IP address to Remote Desktop and login.
</p>

<p>
<img src="https://github.com/user-attachments/assets/5684b67a-ae9f-4f48-bb3e-50625af49fed" />
</p>
<p>
From within my personal computer, I'm observing my IP address through whatismyaddress.com and taking note of it and then observing the IP address within the VM again but through Proton VPN installed and operating
</p>

<p>
<img src="https://github.com/user-attachments/assets/254b1f60-524b-4e47-ac00-c781048b28d1" />
</p>
<p>
I repeat the same process but within the VM with the non-VPN connection and take note of its IP address
</p>

<p>
<img src="https://github.com/user-attachments/assets/6446acb6-f584-414b-8a2d-2d98cb99facc" />
<img src="https://github.com/user-attachments/assets/1c30ec9e-3ed7-4274-9552-db083fea10ab" />
</p>
Sign up for ProtonVPN, login and then download the specific version to the VM [in this case, Windows 10/11 (x64)]
<p>

<p>
<img src="https://github.com/user-attachments/assets/d3660ab9-ab81-4320-a101-ba33e1764266" />
</p>
<p>
Open file, click Ok then next, then install the application. 
</p>

<p>
<img src="https://github.com/user-attachments/assets/6c2b90ed-05a8-4d32-a263-00893f9e1610" />
<img src="https://github.com/user-attachments/assets/61dd805e-230e-4e3d-9f4b-9c496c893f93" />
</p>
<p>
Login to PortonVPN and connect. If applicable, switch the server to a different country for this project.
</p>

<p>
<img src="https://github.com/user-attachments/assets/e95bc1dd-ea24-4ec3-8d32-731cac76f5a8" />
</p>
<p>
Refresh whatismyIPaddress website from earlier and observe the IP address from the server shown for the current country it shows.
</p>


<p>
<img src="https://github.com/user-attachments/assets/15bdb984-a795-462e-a7ad-f37f52752bcd" />
<img src="https://github.com/user-attachments/assets/f709bb60-6097-4652-9cd0-f66e83559e9b" />
<img src="https://github.com/user-attachments/assets/8edaaf3a-45da-4051-bd35-244c7d3261dc" />
</p>
<p>
To conclude the lab, browse any mainstream website and observe any differences between your actual PC and the VM with ProtonVPN in use.
</p>
