<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Enable Internet Information Services (IIS)</h1>
This section outlines the prerequisites and installation of the open-source Help Desk Ticketing System osTicket.<br />






<h2>Environments and Technologies Used:</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used: </h2>

- Windows 10</b> (21H2)
- Mac OSX High Sierra

<h2>Prerequisite:</h2>

- Enable Internet Information Services (IIS)

<h2>Installation Steps:</h2>

<p>
<img src="https://imgur.com/HANbNid.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On Microsoft Azure, I needed a secure Resource Group in order to create a Virtual Machine (VM); which will give me access to remotely compute on Windows 10 using the IP address provided from Azure on my Macbook Pro. After sucesfully logging in Windows 10 virtually, in order to affectively use osTicket, I needed to install a few programs such as Internet Information Services (IIS) that will essentially give me access to osTicket, C++, and PHP Manager. IIS can be installed from the Control Panel. IIS is needed to create a web server that will allow me to create the osTicket system. After enabling IIS on Windows 10, the second process is downloading the Web Platform Installer.
</p>
<br />

<p>
