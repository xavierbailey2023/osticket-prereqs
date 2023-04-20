<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Create a vm  and network in azure
- Item 2: Enable Internet Information Services(IIS)
- Item 3: Installed PHP Manager for IIS, Rewrite Module, and VC_redist.x86 also unzipped a file to desinated location
- Item 4: Registering new PHP within the IIS
- Item 5: Open osTicket installer from IIS
- Item 6: Create a osTicket database in Heidi SQL
- Item 7: Fill out all information in osTicket Installer
- Item 8: Finished osTicket Installation

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/pwOJVas.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I made a windows 10 virtual machine so that I could install the OS Ticket software in a space that is not limited by my personal computer.
</p>
<br />

<p>
<img src="https://i.imgur.com/45FUDZv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I went to Windows control panel and went to Turn Windows features on or off.  Then I added Internet Information Services and made sure that Application Development Services was also selected.  
</p>
<br />

<p>
<img src="https://i.imgur.com/NnbCqad.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Made a new folder on the computer hard drive named it PHP then I unzipped a folder that I downloaded into the new folder that I created on the virtual machines hard drive.  
</p>
<br />

<p>
<img src="https://i.imgur.com/EXsZP42.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Opened Internet Information services went to PHP Manager and registered the PHP so that I could enable different .dll items later.
</p>
<br />

<p>
<img src="https://i.imgur.com/HQoqUZa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed and opened osTicket installer then went to PHP Manager and enabled php_imap.dll, php_intl.dll, and php_opcache.dll. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ZEe9w6M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed and opened HeidiSQL and created a database for osTicket and created a database for osTicket so that I could complete the installation of osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/gxnhJ3v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Filled out information in osTicket to create helpdesk admin and database setting for my created helpdesk.
</p>
<br />

<p>
<img src="https://i.imgur.com/QU6jU4Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Completed osTicket and logged in as an admin and also Support Center domain where request can be sent to the helpdesk.
</p>
<br />
