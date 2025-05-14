<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - VPN Usage Setup</h1>
This tutorial demonstrates how to use a VPN within a virtual machine to observe changes in IP addresses and web content based on geographic location.<br />

<h2>Video Demonstration</h2>
- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN
- Web Browsers

<h2>Operating Systems Used</h2>
- Windows 10 (21H2)

<h2>Project Objectives</h2>
- Compare public IP addresses across different environments
- Set up a virtual machine in another geographic region
- Use a VPN to simulate access from a third region
- Observe how websites adjust content based on location

<h2>Steps</h2>

<!-- Step 1 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step 1 Image"/>
</p>
<p><b>Step 1:</b> Create a Virtual Machine and compare IPs<br/>
- On your own physical machine, visit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> and save your current IP address to a text file.<br/>
- In Azure, create a Resource Group and deploy a Windows 10 Virtual Machine in a different geographic region (preferably another country).<br/>
- Connect to the VM using Remote Desktop.<br/>
- From within the VM, visit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> again and record the VM’s IP address in your text file.
</p>
<br />

<!-- Step 2 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step 2 Image"/>
</p>
<p><b>Step 2:</b> Set up and connect to Proton VPN<br/>
- On your local machine, sign up for a free Proton VPN account at <a href="https://account.protonvpn.com/signup?plan=free&language=en" target="_blank">ProtonVPN Signup</a>.<br/>
- Back inside the VM, download and install the Proton VPN client.<br/>
- Log in at <a href="https://account.protonvpn.com/login" target="_blank">ProtonVPN Login</a> and connect to a VPN server located in a third country (such as Japan).<br/>
- Once connected, revisit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> from within the VM and record the new VPN-assigned IP address.
</p>
<br />

<!-- Step 3 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Step 3 Image"/>
</p>
<p><b>Step 3:</b> Test region-based browsing behavior<br/>
- While connected to the VPN inside the VM, try visiting websites like Google, Disney, and Amazon.<br/>
- Observe if any content, language, or URLs differ depending on the VPN server's country (e.g., Google may redirect to google.co.jp in Japan).<br/>
- Take notes on any differences in layout, product availability, or language settings.
</p>
<br />
