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
  <img src="https://i.imgur.com/fxzOq3M.png" height="80%" width="80%" alt="Step 1 Image 1"/>
</p>
<p>
  <img src="https://i.imgur.com/5NJJ5i7.png" height="80%" width="80%" alt="Step 1 Image 2"/>
</p>
<p>
  <img src="https://i.imgur.com/wT2oNAP.png" height="80%" width="80%" alt="Step 1 Image 3"/>
</p>
<p><b>Step 1:</b> Create a Virtual Machine and Compare IPs<br/>
- On your actual machine, go to <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> and note your public IP address in a text file.<br/>
- In Azure, create a new Resource Group and deploy a Windows 10 VM in a different country.<br/>
- Connect to the VM via Remote Desktop.<br/>
- From inside the VM, visit the same IP site again and record the new IP in your text file.
</p>
<br />

<!-- Step 2 -->
<p>
  <img src="https://i.imgur.com/X2gY5In.png" height="80%" width="80%" alt="Step 2 Image 1"/>
</p>
<p>
  <img src="https://i.imgur.com/2vKzgQu.png" height="80%" width="80%" alt="Step 2 Image 2"/>
</p>
<p>
  <img src="https://i.imgur.com/hYK8pxV.png" height="80%" width="80%" alt="Step 2 Image 3"/>
</p>
<p><b>Step 2:</b> Sign Up for and Connect to Proton VPN<br/>
- On your physical PC, sign up for a free Proton VPN account at <a href="https://account.protonvpn.com/signup?plan=free&language=en" target="_blank">ProtonVPN Signup</a>.<br/>
- Back in the VM, download and install the Proton VPN client.<br/>
- Log into Proton VPN and connect to a server in a third region (e.g., Japan).<br/>
- Visit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> again and document the VPN IP address.
</p>
<br />

<!-- Step 3 -->
<p>
  <img src="https://i.imgur.com/7oH7ZwE.png" height="80%" width="80%" alt="Step 3 Image"/>
</p>
<p><b>Step 3:</b> Browse and Observe Regional Differences<br/>
- While connected to the VPN in the VM, try accessing Google, Amazon, or Disney.<br/>
- Watch for differences such as alternate languages, URLs (like google.co.jp), or content tailored to the VPN's server region.<br/>
- Document your findings for later comparison.
</p>
<br />
