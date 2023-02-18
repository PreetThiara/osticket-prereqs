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

- Create an Azure Virtual Machine running on windows 10
- Enable Internet Information Services(IIS)
- Install PHP and all other files
- Create PHP Directory
- Install MySQL
- Install osTicket
- osTicket Help desk

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/c4YZgBc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above we have created the virtual machine
<p>
<img src="https://i.imgur.com/w5FL3zZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We are going to use windows 10 and name it VM1 creating username labuser and use password of choice.
<p>
<img src="https://i.imgur.com/iz5sse0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After connecting to Azure VM1 with remote desktop, Right-Click Start menu click Run then type in Control panel. Click on Programs then Turn Windows Features on/off.Check the IIS box & expand using plus button Check World Wide Web box then expand click Application Dev Features then expand and finally Check CGI box followed by clicking OK.
</p>
<img src="https://i.imgur.com/a4by6Ks.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install PHP and all other dependancies using the installation list
</p>
<img src="https://i.imgur.com/Rgy0V5Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a php directory in the c drive 
<p>
<img src="https://i.imgur.com/hZI7uc1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install mysql from list. Use the typical steup and launch configuration after install. Use standard configuration and use a password of your choice.Sql is a database that osTicket relies on.
<p>
<img src="https://i.imgur.com/ifylPYN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install OS help desk from list. Enable extensions by going back to IIS -> default->osTicket. Double click php manager. Click enable or disable an extension. Enable php_imap.dll, php_intl.dll, php_opcache.dll. Install HeidiSQL from list which allows you to connect to MySQL server and setup a database for osTicket to use
<p>
<img src="https://i.imgur.com/6BzCPDi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket is now setup and running. You can log in with credentials entered during the setup. 

<br />
