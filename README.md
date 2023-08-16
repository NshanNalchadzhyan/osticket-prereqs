<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

In this project, I set up osTicket from scratch using the required installation files. Before installing the ticketing system, there are a few necessary steps to follow. This lab is conducted on a Windows 10 Pro Virtual Machine created on the Azure platform. The necessary installation files that are referenced and used are located <a href="https://drive.google.com/drive/u/2/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6">here!</a><br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)
- MySQL

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h1> Summary </h1>

The initial steps of this setup involve enabling Internet Information Services (IIS) before proceeding with the local installation of osTicket. To activate IIS, access the Control Panel, navigate to Programs, and select "Turn Windows Features On or Off." Within this section, enable the necessary IIS components, including the IIS Management Console, CGI, and Application Development Features. Following IIS activation, download and install PHP Manager for IIS, followed by the Rewrite Module. Create a designated folder named C:\PHP to accommodate the contents extracted from the downloaded PHP 7.3.8 zip folder. Install MySQL 5.5.62 and configure it with specified credentials. Subsequently, configure IIS settings within PHP Manager and prepare the system for osTicket installation. Download osTicket v1.15.8, extract the "upload" folder, rename it as "osTicket," and integrate it into the designated directory. Enable necessary PHP extensions through the IIS console. Rename and adjust permissions for the ost-config.php file within the osTicket directory. Employ HeidiSQL to create a MySQL database for osTicket. Complete the osTicket setup by providing the required MySQL credentials. After installation, perform necessary cleanup, including deleting setup folders and adjusting file permissions. With these steps accomplished, osTicket is successfully installed, facilitating a hands-on understanding of ticketing systems for IT support scenarios. This project serves as a foundational experience for my future endeavors in IT, where I will be utilizing ticketing systems to effectively manage and resolve user's IT-related issues within a collaborative team environment.
