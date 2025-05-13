<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Vpn Post Setup</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<!-- Step 1 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 1:</b> From your actual machine (not the VM), browse to <a href="https://whatismyipaddress.com/" target="_blank">https://whatismyipaddress.com/</a>  
and take note of your current IP address. Save it in a text file for comparison later.</p>
<br />

<!-- Step 2 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 2:</b> In Microsoft Azure, create a Windows 10 Virtual Machine in a different geographic region (preferably in another country).  
Log into the VM using Remote Desktop, and again browse to <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a>  
to record the VM's IP address.</p>
<br />

<!-- Step 3 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 3:</b> On your actual computer (not the VM), sign up for the free version of Proton VPN at  
<a href="https://account.protonvpn.com/signup?plan=free&language=en" target="_blank">https://account.protonvpn.com/signup</a></p>
<br />

<!-- Step 4 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 4:</b> Inside the Virtual Machine, download and install the Proton VPN client.  
Login at <a href="https://account.protonvpn.com/login" target="_blank">Proton VPN login</a> and connect to a VPN server in a third location (e.g., Japan).</p>
<br />

<!-- Step 5 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 5:</b> Once connected to the VPN, visit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a>  
again from the VM and record the new VPN-assigned IP address.</p>
<br />

<!-- Step 6 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step Image"/>
</p>
<p><b>Step 6:</b> Try browsing websites such as Google, Disney, or Amazon from the VM while connected to the VPN.  
Observe any changes in content, language, or URL based on the VPN server location (e.g., google.co.jp instead of google.com).</p>
<br />

