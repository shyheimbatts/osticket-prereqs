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

- Windows 11 Pro</b> (24H2)

<h2>List of Prerequisites </h2>

- Azure Account (to deploy the virtual machine)

- Windows 11 Virtual Machine (created in Azure)

- Administrator Access to the virtual machine

- Remote Desktop Connection software

- osTicket Installation Files (downloaded from the official site or as provided in lab resources)

- IIS (Internet Information Services) enabled with CGI support

- PHP (appropriate version installed)

- MySQL 5.5 (for the osTicket database)

- HeidiSQL (for managing the MySQL database)

- Microsoft Visual C++ Redistributable (required for PHP/MySQL)

<h2>Installation Steps</h2>

- Task 1 Create the Virtual Machine(VM)                                                                       
- Task 2 Log into the Virtual Machine(VM) with Remote Desktop
- Task 3
- Task 4
- Task 5
- Task 6
- Task 7
- Task 8
- Task 9
- Task 10
- Task 11
- Task 12
- Task 13
- Task 14
- Task 15
- Task 16
- Task 17
- Task 18
- Task 19

  <h2></h2>

  
  <p>
 **Task 1** - Start by clicking the "Create" button, then select the "Virtual Machine" option from the drop-down menu. Next, under the **Basics** tab, scroll down to **Resource group**, where you see the red arrow, and click **Create new**. The name for the resource group will be **osTicket**. After that, select **OK** and scroll down to **Image**. Select **Windows 11 Pro, Version 24H2 x64 Gen2** from the drop-down menu next to **Image** and for the **Size** select **Standard _D2s_v3 - 2 Virtual Central Processing Unit(vcpus), 8 GiB Memory**. Scroll down to fill in the "Username" and "Password" section with something that's most memorable to you. Be sure to click the **checkmark** under the licensing section and click **review + create**.
  
<p>
<img width="1440" height="611" alt="Screenshot 2025-10-20 at 3 14 32 PM" src="https://github.com/user-attachments/assets/f333ba8d-e42e-49bf-9d34-ca1a658aca71" />
<img width="1429" height="768" alt="resource group screenshot 2026-01-21 at 1 55 14 PM" src="https://github.com/user-attachments/assets/fe8e468f-c15c-4b48-b2ca-b5b64a1a46f4" />
<img width="1431" height="771" alt="virtual machine 2026-01-21 at 2 00 52 PM" src="https://github.com/user-attachments/assets/481dc1c9-44e2-4d47-a25a-be14cf3dc068" />
<img width="1235" height="651" alt="Screenshot 2026-01-21 at 2 25 07 PM" src="https://github.com/user-attachments/assets/de5ee6fa-9267-4ea3-bf40-9db011acf218" />
  <img width="1428" height="775" alt="create vm" src="https://github.com/user-attachments/assets/3d17ca6a-c84c-42bc-add2-44b3167d0392" />
<img width="1241" height="609" alt="Screenshot 2026-01-21 at 2 39 47 PM" src="https://github.com/user-attachments/assets/b979bd08-1e98-4643-9e19-4a5aaae55f22" />
  <p>
    
**Task 2** - Select the "Virtual Machine" icon from Azure’s homescreen, then go to the osTicket VM that was just created and copy the Public IP address next to the red arrow. 

</p>

<img width="1424" height="227" alt="azure home" src="https://github.com/user-attachments/assets/1869ac21-30ab-4ffc-8f23-a5615f404816" />
<img width="1241" height="609" alt="Screenshot 2026-01-21 at 2 39 47 PM" src="https://github.com/user-attachments/assets/0ff1c89d-738a-4d3d-9bf4-e742025280d5" />
<img width="1244" height="647" alt="Screenshot 2026-01-22 at 9 36 48 AM" src="https://github.com/user-attachments/assets/2e115839-75f0-4e63-895a-2f123101fe0f" />
  <img width="712" height="645" alt="Screenshot 2026-01-22 at 12 51 30 PM" src="https://github.com/user-attachments/assets/24dd8445-7166-4189-a987-fb1d3b243a8b" />
 <img width="710" height="641" alt="Screenshot 2026-01-22 at 12 51 56 PM" src="https://github.com/user-attachments/assets/544cb94b-3e49-4e63-8590-fe79a4f28745" />
  <img width="707" height="643" alt="Screenshot 2026-01-22 at 12 52 21 PM" src="https://github.com/user-attachments/assets/55e15039-89cd-4e28-8a4e-6f260fa831a2" />

<p>

**Task 3** -
  
</p>


<p>
<img width="629" height="776" alt="Screenshot 2026-01-22 at 1 14 25 PM" src="https://github.com/user-attachments/assets/3c839b58-ecfe-4d32-a4aa-d4aca8101eca" />
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
