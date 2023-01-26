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

- Azure Virtual Machine
- osTicket install Files
- Heidi SQL

<h2>Installation Steps</h2>
Overview
<p>
<img src="https://i.ibb.co/VgFPwqw/Screen-Shot-2023-01-25-at-8-09-29-PM.png" alt="Screen-Shot-2023-01-25-at-8-09-29-PM" border="0">
</p>
<p>
Create a resource group in Microsoft Azure.
<p>
<img src="https://i.ibb.co/Fg1RCWd/Screen-Shot-2023-01-25-at-8-26-12-PM.png" alt="Screen-Shot-2023-01-25-at-8-26-12-PM" border="0">
</p>
Create a virtual machine in Azure.
<img src="https://i.ibb.co/YP8fttX/Screen-Shot-2023-01-25-at-8-36-31-PM.png" alt="Screen-Shot-2023-01-25-at-8-36-31-PM" border="0">
</p>
Open Remote Desktop or Microsoft Remote Desktop for MAC
</p>
<img src="https://i.ibb.co/0fbdCG6/Screen-Shot-2023-01-25-at-8-41-53-PM.png" alt="Screen-Shot-2023-01-25-at-8-41-53-PM" border="0">
</p>
Turn on IIS (Internet Information Services). Control Pannel - Programs and Feautures
</p>
<img src="https://i.ibb.co/DgBmdy2/Screen-Shot-2023-01-25-at-8-46-49-PM.png" alt="Screen-Shot-2023-01-25-at-8-46-49-PM" border="0">

Install Microsoft Web Platform Installer. Add (MySQL 5.5) - Add All Simple Versions Of X86PHP Until 7.3
<img src="https://i.ibb.co/QMRKng6/Screen-Shot-2023-01-26-at-10-19-49-AM.png" alt="Screen-Shot-2023-01-26-at-10-19-49-AM" border="0">
</p>
Install osTicket v1.15.8.
</p>
<img src="https://i.ibb.co/k4LW5M5/Screen-Shot-2023-01-25-at-8-55-20-PM.png" alt="Screen-Shot-2023-01-25-at-8-55-20-PM" border="0">
</p>
Go to IIS, Sites/Default/osTicket, click PHP Manager, enable PHP_imap.dll, enable PHP_intl.dll, enable PHP_opcache.dll
</p>
<img src="https://i.ibb.co/HXh8gm5/Screen-Shot-2023-01-26-at-10-36-08-AM.png" alt="Screen-Shot-2023-01-26-at-10-36-08-AM" border="0">
</p>
Go to c:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php rename the file to c:\inetpub\wwwroot\osTicket\include\ost-config.php Assign permissions to ost-config.php Disable inheritance->Removeall New Permissions->Everyone->all
</p>
<img src="https://i.ibb.co/Wp99qLh/Screen-Shot-2023-01-26-at-10-43-47-AM.png" alt="Screen-Shot-2023-01-26-at-10-43-47-AM" border="0">
</p>
Continue setting up osTicket. Name Helpdesk and give default email.
</p>
<img src="https://i.ibb.co/Kzr7PrD/Screen-Shot-2023-01-26-at-10-50-03-AM.png" alt="Screen-Shot-2023-01-26-at-10-50-03-AM" border="0">
</p>
Download and install HeidiSQL
</p>
<img src="https://i.ibb.co/sWRt0DC/Screen-Shot-2023-01-26-at-10-53-43-AM.png" alt="Screen-Shot-2023-01-26-at-10-53-43-AM" border="0">
</p>
osTicket is now ready
</p>
<img src="https://i.ibb.co/xST0MFB/Screen-Shot-2023-01-26-at-10-55-28-AM.png" alt="Screen-Shot-2023-01-26-at-10-55-28-AM" border="0">
