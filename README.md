<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Laptop or Desktop
- Internet Connection
- Microsoft Azure Subscription 
- Created Virtual Machine(VM) in Azure Using Windows 10
- Remote Desktop Protocol(RDP) (preinstalled on Windows / app available on MAC)

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/EspEfb5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy the public IP Address from your virtual machine. RDP into VM from laptop. Enable IIS from control panel(Programs>Turn Windows features on or off>Internet Information Services>World Wide Web>Application Developement Features>Check CGI)
</p>
<br />

<p>
<img src="https://i.imgur.com/HlcyADK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install and download PHP Manager for IIS and Rewrite Module. Create the directory C:\PHP. Download PHP and unzip the files into the newly created folder. Download and install VCredist 86 and Mysql5.5.62. Create user and password for Mysql
</p>
<br />

<p>
<img src="https://i.imgur.com/r3NgCm1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as Administrator and register PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/qbq377O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install osTicket. Set the system settings and create admin user. Be sure to write down usernames and passwords. Will have to install Heidesql to connect to mysql this will set up the database for osticket to use.
</p>
<br />

<p>
<img src="https://i.imgur.com/ehbfU5R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket is fully installed.
</p>
<br />
