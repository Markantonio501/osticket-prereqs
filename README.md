# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Instillation</h1>
This tutorial outlines the installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Create A Virtual Machine](https://www.youtube.com/watch?v=dP0vNd5K2x8)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installating osTicket Prerequisites </h2>

- Step 1  
-Our first step is creating a resouce group
-Once a resource group has been created, we will create a Virtual Machine (VM) with 2-4 Virtual CPUs. While creating the VM, allow it to create a new Virtual      Network (VNET)
- Step 2 To make this simple for us we can name the VM (Vm-osticket) our USERNAME:labuser and our PASSWORD:osTicketPassword1!
- Step 3 After creating the user name and password we can now install/enable IIS in windows with CGI (CGI is needed to be able to install the file named (PHPManagerForIIS_V1.5.0.msi) World Wide Web Services -> Application Development Features -> [X] CGI

- Step 4 After completing step 3 now we can continue with the installation files that can be accessed through this link https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
- Step 5 Under file explorer click on download and you will see all of the installation file you can now go ahead and instal the files (PHPManagerForIIS_V1.5.0.msi),(rewrite_amd64_en-US.msi),(VC_redist.x86.exe),and (mysql-5.5.62-win32.msi)
  *For the file (mysql-5.5.62-win32.msi) you will proceed in this order-Typical Setup ->
Launch Configuration Wizard (after install) ->
Standard Configuration ->
Password1
- Step 6 For the specific file (php-7.3.8-nts-Win32-VC15-x86.zip) we will create a directory or new file under the C: Drive and name it PHP. We will then unzip the contents into the new file Named PHP.
- Step 7 Our final step to installation will be to Open IIS as an admin and register PHP from within IIS
- There will be images of the entire process to help you through the installation process Thank you!

 


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
