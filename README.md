# VPN-Setup-Usage
<p align="center">
  <img src="https://i.imgur.com/qtrcixw.png)" alt="VPN"/>
</p>

<h1>Virtual Private Network Setup and Usage</h1>
In this illustration, I will set up a VPN on A virtual machine and observe how it is used. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Steps</h2>

- Create a Virtual Machine (Windows 10 OS) within Azure in a different location
- Remote desktop connect into the VM
- Signup/download Proton VPN
- Login to VPN on VM and choose different location on VPN server
- Observe the changes of the location with https://whatismyipaddress.com/


<h2>Actions and Observations</h2>


<p>
First, I created a Virtual Machine in Azure with the region located in Korea Central. When creating a virtual machine in Azure, the virtual network and Network interface get created at the same time.
</p>
<p>
<img src="https://i.imgur.com/YhhDCf6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
After creating the virtual machine, I created an account on ProtonVPN, remoted into the VM and installed the app on the VM in Korea. Here I then set the VPN server in Japan. 
</p>
<p>
<img src="https://i.imgur.com/x0toayU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />


<p>
Lastly, I observed the changes that were made by checking https://whatismyipaddress.com/ as well as other web pages. Now, if exploring webpages, they are now set in Japan.
</p>
<p>
<img src="https://i.imgur.com/d2pjEpl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/Y2xqD9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/QzTvhhE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
