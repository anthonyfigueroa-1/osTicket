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
<img src="https://i.imgur.com/zKJECfQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Create the directory C:\PHP
</p>
<br />
  
<p>
<img src="https://i.imgur.com/gzxGX8Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/o4gqp4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install VC_redist.x86.exe.
</p>
<br />

<p>
<img src="https://i.imgur.com/LXvbPLs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/aFE3ptb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
    - Typical Setup ->
    - Launch Configuration Wizard (after install) ->
    - Standard Configuration ->
    - Password1

</p>
<br />
  
<p>
<img src="https://i.imgur.com/bXkb3wZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Open IIS as an Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/2QVRzzU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Register PHP from within IIS
</p>
<br />
  
<p>
<img src="https://i.imgur.com/U2JP2IM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Reload IIS (Open IIS, Stop and Start the server)
</p>
<br />
  
<p>
<img src="https://i.imgur.com/4orxr1P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Noh9pIT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Install osTicket v1.15.8
    - Download osTicket from the Installation Files Folder
    -  Extract and copy “upload” folder to c:\inetpub\wwwroot
    -  Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”
  - Reload IIS (Open IIS, Stop and Start the server)
</p>
<br />
  
<img src="https://i.imgur.com/U2Cpghy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Go to sites -> Default -> osTicket
    - On the right, click “Browse *:80”
</p>
<br />
  
<img src="https://i.imgur.com/RaIFlcR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - Note that some extensions are not enabled
    - Go back to IIS, sites -> Default -> osTicket
    - Double-click PHP Manager
    - Click “Enable or disable an extension”
      - Enable: php_imap.dll
      - Enable: php_intl.dll
      - Enable: php_opcache.dll
    - Refresh the osTicket site in your browse, observe the changes
</p>
<br />

<img src="https://i.imgur.com/o4gqp4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install VC_redist.x86.exe.
</p>
<br />

<img src="https://i.imgur.com/o4gqp4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install VC_redist.x86.exe.
</p>
<br />

<img src="https://i.imgur.com/o4gqp4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install VC_redist.x86.exe.
</p>
<br />

<img src="https://i.imgur.com/o4gqp4D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  - From the Installation Files, download and install VC_redist.x86.exe.
</p>
<br />
