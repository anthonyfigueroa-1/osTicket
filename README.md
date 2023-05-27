<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Install</h1>
This tutorial outlines the installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites<h2>

- Have a virtual machine within Azure running Windows 10.
- [Install Files](https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)

<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/DZkA3YW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Install / Enable IIS in Windows WITH CGI and Common HTTP Features
- World Wide Web Services -> Application Development Features ->
  - [X] CGI
  - [X] Common HTTP Features

</p>
<br />

<p>
<img src="https://i.imgur.com/h2mHARu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
</p>
<br />

<p>
<img src="https://i.imgur.com/VkZNYN6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install the Rewrite Module (rewrite_amd64_en-US.msi)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will now allow anyone to create tickets so to do that we will go into settings, while still in the admin panel, and then to user settings. From there we make registration required: require registration and login to create tickets.
</p>
<br />
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will now allow anyone to create tickets so to do that we will go into settings, while still in the admin panel, and then to user settings. From there we make registration required: require registration and login to create tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will now allow anyone to create tickets so to do that we will go into settings, while still in the admin panel, and then to user settings. From there we make registration required: require registration and login to create tickets.
</p>
<br />
