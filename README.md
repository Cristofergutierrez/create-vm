<p align="center">
<img src="https://imgur.com/nusAuqu.png" alt="Windows logo"/>
</p>

<h1>Windows Virtual Machine- Prerequisites and Installation</h1>
This tutorial outlines the installation of Windows in a Azure virtual machine.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>
- Create a free Microsoft Azure account

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/PFDhNU4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Choose a name and region for your resource group.
</p>
<br />

<h2>Setup Azure Virtual Machine</h2>

<p>
<img src="https://i.imgur.com/JWq3svB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Home--> Virtual Machines--> Create Azure Virtual Machine</br>
Select the resource group we just created and fill in the virtual machine name and administrator account. Then select Windows 10 Pro for the image, remember the more cpus and memory the better performance the vm will have.
</p>
<br />

<h2>REVIEW + CREATE</h2>
<p>
<img src="https://imgur.com/X6P5IxS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Acess your Virtual Machine</h2>

<p>
<img src="https://imgur.com/RhWQUBk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Home--> Virtual Machines--> labuser</br>
Copy your virtual machines Public IP Address
</p>
<br />

<h2>Launch Remote Desktop</h2>

<p>
<img src="https://imgur.com/bgz6J8M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your own computer open Remote Desktop Connection and paste in the Virtual Machines Public IP Adress and then click connect. 
</p>
<p>
<img src="https://imgur.com/qfTccmK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After logging in using the credentials we made you will now be inside your windows 10 virtual machine hosted on Microsoft Azure
</p>
<br />

