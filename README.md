# <p align="center">
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



<h2>Installation Steps</h2>

<p>

![Created a Virtual Machine and a Resource Group for the VM inside of Microsoft Azure Cloud Platform (Step-1)](https://github.com/user-attachments/assets/4353db93-b496-424d-b0a9-c0d3184ce349)


</p>
<p>
Created a Virtual Machine and a Resource Group for the VM inside of Microsoft Azure Cloud Platform (Step-1)
</p>
<br />

<p>

![Unzipped osTicket Installation Folder inside of Azure Virtual Machine (Step-2)](https://github.com/user-attachments/assets/6444d919-289d-4542-9244-0bb3db72d0fe)

</p>
<p>
Unzipped osTicket Installation Folder inside of Azure Virtual Machine (Step-2)
</p>
<br />

<p>

![Installed PHP Manager for IIS inside Virtual Machine (Step-3)](https://github.com/user-attachments/assets/7021b61f-7f13-44cf-9f90-91289aad0770)

</p>
<p>
Installed PHP Manager for IIS inside Virtual Machine (Step-3) - IIS Manager is a graphical user interface (GUI) tool used to manage Internet Information Services (IIS), which is a web server from Microsoft. It allows administrators to configure websites, manage application pools, set up security features, and monitor performance for web applications hosted on Windows servers.

A Graphical User Interface (GUI) is a visual way for users to interact with software or devices, as opposed to text-based interfaces like command-line interfaces (CLI). GUIs use graphical elements such as windows, icons, buttons, and menus to make software easier to use, especially for non-technical users.
</p>
<br />

<p>

![Installed the Rewrite Module for IIS inside Azure VM (Step-4)](https://github.com/user-attachments/assets/444a9b43-783d-4c00-959c-86ec1efb2b50)

</p>
<p>
Installed the Rewrite Module for IIS inside Azure VM (Step-4) - The Rewrite Module in osTicket refers to a feature in the web server (like Apache or IIS) that allows for URL rewriting. It enables clean, user-friendly URLs by transforming complex or dynamic URLs into simpler, more readable ones. This module is often required during the installation of osTicket to improve usability and SEO by ensuring URLs are easy to navigate and index.
</p>
<br />

<p>

![Created a folder on the C-Drive inside the Azure VM and named it PHP (Step-5)](https://github.com/user-attachments/assets/e0bd4a30-b4f4-4e30-ab0b-1685e25ff862)

</p>
<p>
Created a folder on the C-Drive inside the Azure VM and named it PHP (Step-5)
</p>
<br />

<p>

![Unzipped the PHP Installation Folder straight into the PHP folder we just created on the Virtual Machines C-Drive (Step-6)](https://github.com/user-attachments/assets/3c477847-5435-4fad-9df0-146b2c907ce5)

</p>
<p>
Unzipped the PHP Installation Folder straight into the PHP folder we had just created on the Virtual Machines C-Drive (Step-6)
</p>
<br />

<p>

![Installed VC Redistributable out of the osTicket Installation Files folder (Microsoft C++ Visuals) (step-7)](https://github.com/user-attachments/assets/cfd7aa3d-67a9-4fc5-b711-f340ac5f9a6e)

</p>
<p>
Installed VC Redistributable out of the osTicket Installation Files folder (Microsoft C++ Visuals) (step-7) - Microsoft C++ Visuals, often referring to Microsoft Visual C++ Redistributables, are runtime libraries required to run applications developed using Microsoft Visual C++. These libraries include essential components of C++ like standard libraries, which are needed for software to execute properly on a Windows system. Many programs depend on these redistributables to function correctly.
</p>
<br />

<p>

![After installing MySQL, we ran the application and set a username and password (Step-8)](https://github.com/user-attachments/assets/d8e53096-f2e6-4136-aae9-580632c9ce09)

</p>
<p>
After installing MySQL, we ran the application and set a username and password (Step-8) - MySQL is an open-source relational database management system (RDBMS) that uses structured query language (SQL) to manage and manipulate data. It's widely used for web applications and services, supporting large-scale data storage and retrieval. MySQL is known for its speed, reliability, and ease of use, and it is commonly paired with PHP and Apache in the LAMP (Linux, Apache, MySQL, PHP) stack.
</p>
<p>
<br />

<p>

![Opened IIS as an admin to begin configuring things inside our webserver (Step-9)](https://github.com/user-attachments/assets/fe1d307a-1d76-4509-950b-24eecfec0ed8)

</p>
<p>
Opened IIS as an admin to begin configuring things inside our webserver (Step-9)
</p>
<p>
<br />

<p>

![Registered PHP inside IIS - basically made web server aware of the php file location (Step-10)](https://github.com/user-attachments/assets/1eb38c88-c904-429b-af83-53e5058c1236)

</p>
<p>
Registered PHP inside IIS - basically made web server aware of the php file location (Step-10) - PHP is a popular open-source scripting language used mainly for web development. It runs on the server and helps create dynamic web pages by interacting with databases and generating HTML.

Registering PHP in IIS means setting up IIS to run PHP scripts, so websites using PHP can work properly on the server.
</p>
<p>
<br />

<p>

![Extracted files from osTicket zip folder inside osTickets Installation Files folder (Step-11)](https://github.com/user-attachments/assets/81a573f3-7d6c-40ab-bfa1-ccd8946d0284)

</p>
<p>
Extracted files from osTicket zip folder inside osTickets Installation Files folder (Step-11)
</p>
<p>
<br />

<p>

![Copied ostcket-upload folder into C Drive-inetpub-wwwroot Folder and rename Upload to osTicket (Step-12)](https://github.com/user-attachments/assets/d7a5a7bc-13df-4518-8816-7461e4a2a7f6)

</p>
<p>
Copied ostcket/"upload folder" into C:/inetpub/wwwroot Folder and renamed "Upload" to "osTicket" (Step-12)
</p>
<p>
<br />

<p>

![Reloaded IIS - Stopped and Restarted web server (Step-13)](https://github.com/user-attachments/assets/6bf9dbbd-b985-44bb-beee-6d94ef1fdd77)

</p>
<p>
Reloaded IIS - Stopped and Restarted web server (Step-13) 
</p>
<p>
<br />

<p>

![Loaded osTicket webpage inside IIS Manager (Step-14)](https://github.com/user-attachments/assets/43ad1385-6fd2-4f91-84dc-3354af9a7a6a)

</p>
<p>
Loaded osTicket webpage inside IIS Manager (Step-14)
</p>
<p>
<br />

<p>

![Used IIS Manager to enable PHP extensions for osTicket (Step-15)](https://github.com/user-attachments/assets/30bb6e4d-5df8-41e6-8c75-7619293a7a37)

</p>
<p>
Used IIS Manager to enable PHP extensions for osTicket (Step-15)
</p>
<p>
<br />

<p>

![The PHP Extensions that got enabled in IIS Manager (Step-16)](https://github.com/user-attachments/assets/c6a85184-4a73-4c20-a42f-54f85023f75e)

</p>
<p>
The PHP Extensions that got enabled in IIS Manager (Step-16) - PHP extensions are modules that add specific functionalities to PHP, enabling features like database connections, image processing, or encryption. They enhance PHP's capabilities by providing additional functions and classes that developers can use in their applications.
</p>
<p>
<br />

<p>

![Observed the extensions that are now enabled on osTickets webpage (Step-17)](https://github.com/user-attachments/assets/ef26ce20-08ea-4b12-b73d-512010f4c473)

</p>
<p>
Observed the extensions that are now enabled on osTickets webpage (Step-17)
</p>
<p>
<br />

<p>

![Inside the osTicket-Include Folder we renamed ost-sampleconfig to ost-config (Step-18)](https://github.com/user-attachments/assets/994565f6-188a-4351-af7e-36a4352736bc)

</p>
<p>
Inside the osTicket/Include Folder we renamed "ost-sampleconfig" to "ost-config" (Step-18)
</p>
<p>
<br />

<p>

![Disabled Inheritance in ost-config file to stip away all current permissions and make our own (Step-19)](https://github.com/user-attachments/assets/6012d24a-2cca-4cbc-9953-6aa0d3ba3888)

</p>
<p>
Disabled Inheritance in "ost-config" file to strip away all current permissions and make our own after they are gone (Step-19)
</p>
<p>
<br />

<p>

![Created a permission inside ost-config file that allowed everyone full access - not good to do in real life but osTicket needed full control to configuration file for lab (Step-20)](https://github.com/user-attachments/assets/9d5e1162-a911-4a24-8fe5-0bdbcd5997d6)

</p>
<p>
Created a permission inside "ost-config" file that allowed everyone full access - not good to do in real life but osTicket needed full control to configure file for the lab (Step-20)
</p>
<p>
<br />

<p>

![Continued in osTicket webpage and filled out information for admin account and URL and email (Step-21)](https://github.com/user-attachments/assets/7bbb416f-b2d3-4b39-a63f-4be230808fa5)

</p>
<p>
Continued in osTicket webpage and filled out information for admin account, URL, and email (System Settings) (Step-21)
</p>
<p>
<br />

<p>

![Installed Heidi SQL inside osTicket Installation folder to configure a database for osTicket (Step-22)](https://github.com/user-attachments/assets/3aa9d9c5-7dc8-4910-a524-fce84ec76318)

</p>
<p>
Installed Heidi SQL inside osTicket Installation folder to configure a database for osTicket (Step-22) - HeidiSQL is a free, open-source database management tool that allows users to manage and interact with MySQL, MariaDB, and PostgreSQL databases. It provides a user-friendly interface for tasks such as creating, editing, and deleting database tables, running SQL queries, and managing users and permissions, making it easier to work with databases without extensive command-line knowledge.
</p>
<p>
<br />

<p>

![Opened HeidiSQL and connected to the database then created a new session or database and named it osTicket (Step-23)](https://github.com/user-attachments/assets/4c91ed69-4284-4132-92c2-27bd2359ea6f)

</p>
<p>
Opened HeidiSQL and connected to the database then created a new session or database and named it "osTicket" (Step-23)
</p>
<p>
<br />

<p>

![Continued in osTicket web page and filled out information for MySQL database to connect to it and began to install (Step-24)](https://github.com/user-attachments/assets/e48f4c63-a5f6-4498-b0f7-32579f556ec4)

</p>
<p>
Continued in osTicket web page and filled out information for MySQL database to get connected and began to install (Step-24)
</p>
<p>
<br />

<p>

![Refreshed MySQL osTicket database and observed all of the files that were now in the osTicket folder (Step-25)](https://github.com/user-attachments/assets/770e5c59-0c79-455b-913d-84ef58c1eda7)

</p>
<p>
Refreshed MySQL osTicket database and observed all of the files that were now in the osTicket folder (Step-25)
</p>
<p>
<br />

<p>

![Using different URLs we successfully logged onto osTicket as an admin and a local host and completed creating a ticket enviroment simulation (Step-26)](https://github.com/user-attachments/assets/7e9102ee-4f9a-40dd-ae62-e974526d736d)

</p>
<p>
Using different URLs we successfully logged onto osTicket as "an admin" and "a local host" and completed creating a ticketing-enviroment simulation (Step-26)
</p>
