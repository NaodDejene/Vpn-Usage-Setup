<p align="center">
<img src="https://i.imgur.com/KjTsfwa.png" alt="osTicket logo"/>
</p>

<h1>osTicket - VPN Usage Setup</h1>
This tutorial demonstrates how to configure and test a VPN within a virtual machine to explore regional IP address changes and content localization.

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
- Record your real-world IP address  
- Create and configure a VM in another region  
- Install and use a VPN to connect through a third country  
- Observe and document changes in regional web behavior  

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
<p><b>Step 1:</b> Create a Virtual Machine and Record IPs<br/>
- On your local machine, go to <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> and save your current IP in a text file.<br/>
- In Azure, create a resource group and deploy a Windows 10 virtual machine in a different region (e.g., a foreign country).<br/>
- Use Remote Desktop to log into the VM and revisit the same site to capture and record that IP.
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
- On your host machine, sign up for the free plan from Proton VPN:  
  <a href="https://account.protonvpn.com/signup?plan=free&language=en" target="_blank">Proton VPN Signup</a>.<br/>
- In the virtual machine, install the Proton VPN client.<br/>
- Log into your account and connect to a VPN server in a third location, such as Japan.<br/>
- Visit <a href="https://whatismyipaddress.com/" target="_blank">whatismyipaddress.com</a> again and save the VPN-assigned IP to your file.
</p>
<br />

<!-- Step 3 -->
<p>
  <img src="https://i.imgur.com/7oH7ZwE.png" height="80%" width="80%" alt="Step 3 Image 1"/>
</p>
<p><b>Step 3:</b> Observe Location-Based Content Differences<br/>
- While connected to the VPN from the VM, visit major sites like Google, Disney, or Amazon.<br/>
- Look for signs that content is being served based on your VPN’s region: different URLs (e.g., google.co.jp), language preferences, or region-specific promotions.<br/>
- Take note of these variations for documentation and comparison.
</p>
<br />
