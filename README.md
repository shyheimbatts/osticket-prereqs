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
 **Task 1** - Start by clicking the "Create" button, then select the "Virtual Machine" option from the drop-down menu. Next, under the **Basics** tab, scroll down to **Resource group**, where you see the red arrow, and click **Create new**. The name for the resource group will be **osTicket**. After that, select **OK** and scroll down to the **image**. Select **Windows 11 Pro, Version 24H2 x64 Gen2** from the drop-down menu next to **Image** and for the **Size** select **Standard _D2s_v3 - 2 Virtual Central Processing Unit(vcpus), 8 GiB Memory**. Scroll down to fill in the **"Username"** and **"Password"** section with something that's easy to remember. Be sure to click the **checkmark** under the licensing section and click **review + create**. To deploy the Virtual Machine, click **Create**. The Virtual Machine is created and ready for use.


<p>
<img width="1440" height="611" alt="Screenshot 2025-10-20 at 3 14 32 PM" src="https://github.com/user-attachments/assets/f333ba8d-e42e-49bf-9d34-ca1a658aca71" />
<img width="1429" height="768" alt="resource group screenshot 2026-01-21 at 1 55 14 PM" src="https://github.com/user-attachments/assets/fe8e468f-c15c-4b48-b2ca-b5b64a1a46f4" />
<img width="1431" height="771" alt="virtual machine 2026-01-21 at 2 00 52 PM" src="https://github.com/user-attachments/assets/481dc1c9-44e2-4d47-a25a-be14cf3dc068" />
<img width="1235" height="651" alt="Screenshot 2026-01-21 at 2 25 07 PM" src="https://github.com/user-attachments/assets/de5ee6fa-9267-4ea3-bf40-9db011acf218" />
  <img width="1428" height="775" alt="create vm" src="https://github.com/user-attachments/assets/3d17ca6a-c84c-42bc-add2-44b3167d0392" />
<img width="1241" height="609" alt="Screenshot 2026-01-21 at 2 39 47 PM" src="https://github.com/user-attachments/assets/b979bd08-1e98-4643-9e19-4a5aaae55f22" />
  <p>
    
**Task 2** - To log into the Virtual Machine using remote desktop select the **"Virtual Machine"** icon from Azure’s homescreen, then go to the **osTicket VM** that was just created and copy the Public IP address next to the red arrow. Paste the **public IP address** in the **Add PC(PC name)** section of remote desktop and in the **Friendly name** section put osTicket then select **"Add"**. Now click on the VM created in remote desktop, enter in the username and password that was created during task 1

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
<img width="676" height="196" alt="Screenshot 2025-10-20 at 11 08 14 PM" src="https://github.com/user-attachments/assets/74730ace-83bd-41e7-b104-fd1d78c695b3" />
<img width="356" height="131" alt="Screenshot 2025-10-20 at 11 09 50 PM" src="https://github.com/user-attachments/assets/686e3420-f5d0-4008-9139-fb4fe1deef10" />
<img width="1119" height="579" alt="Screenshot 2025-10-20 at 11 10 41 PM" src="https://github.com/user-attachments/assets/cbfaebea-d61c-4b2a-a182-8e04c8e304a1" />
<img width="345" height="505" alt="Screenshot 2025-10-20 at 11 17 22 PM" src="https://github.com/user-attachments/assets/a964643a-d212-4b70-a274-51c7ff48d12e" />
  
</p>


 </p>

  

  <img width="608" height="447" alt="Screenshot 2025-10-20 at 11 18 54 PM" src="https://github.com/user-attachments/assets/4f5a1709-800d-4557-8593-c84bd26f6555" />
  <img width="1440" height="900" alt="Screenshot 2025-10-20 at 11 20 33 PM" src="https://github.com/user-attachments/assets/5bd5f98d-948a-4c4d-ae31-372021cae0f3" />
  <img width="312" height="108" alt="Screenshot 2025-10-21 at 7 47 37 PM" src="https://github.com/user-attachments/assets/01fa9c5c-65f3-4557-b41e-206b000ac61e" />
  <img width="1115" height="579" alt="Screenshot 2025-10-21 at 7 48 29 PM" src="https://github.com/user-attachments/assets/517d708c-ae51-426e-b69e-bf086e34f071" />
   <img width="1440" height="900" alt="Screenshot 2025-10-21 at 7 49 24 PM" src="https://github.com/user-attachments/assets/d11ac809-631d-4f73-a4b8-c94a58b61512" />
  <img width="1440" height="900" alt="Screenshot 2025-10-21 at 7 49 46 PM" src="https://github.com/user-attachments/assets/3b7d192f-9888-4d13-9c15-d0fd774e2374" />
  <img width="1440" height="900" alt="Screenshot 2025-10-21 at 7 51 18 PM" src="https://github.com/user-attachments/assets/27f5a98a-3e21-4bcf-8992-55a790932f7f" />
  <img width="1440" height="900" alt="Screenshot 2025-10-21 at 7 52 40 PM" src="https://github.com/user-attachments/assets/5a6e991e-e2f6-4da2-814d-8c6f538ff62c" />
  <img width="448" height="738" alt="Screenshot 2025-10-28 at 6 09 36 PM" src="https://github.com/user-attachments/assets/88ef9ed6-1b7c-4f12-a517-f148e1434c2f" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 12 05 PM" src="https://github.com/user-attachments/assets/25a06cf4-6fc4-4651-bf3a-a4adf91b925d" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 12 27 PM" src="https://github.com/user-attachments/assets/6d44c604-7711-4eef-bc20-9f1eddfefad1" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 13 02 PM" src="https://github.com/user-attachments/assets/47ed0e25-da4d-43d3-aa3e-ce901cae2374" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 13 40 PM" src="https://github.com/user-attachments/assets/cc0be937-8087-4fc9-97ee-670109b6cba8" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 14 21 PM" src="https://github.com/user-attachments/assets/a9e813c7-6b97-49a8-88f7-ffa99583e2ab" />
  <img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 14 42 PM" src="https://github.com/user-attachments/assets/02c28c66-92c3-498d-8d6a-3ad1ef2ccd64" />
<img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 21 34 PM" src="https://github.com/user-attachments/assets/f9913afb-15ba-40a4-b790-d67171b11736" />
<img width="1440" height="900" alt="Screenshot 2025-10-28 at 6 22 41 PM" src="https://github.com/user-attachments/assets/e6bf4ab8-1e65-42ba-b305-bfe0eba5c34d" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 22 22 PM" src="https://github.com/user-attachments/assets/b8674570-7309-48e2-8b00-a96cef659164" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 22 56 PM" src="https://github.com/user-attachments/assets/c7b576e6-77cd-4dad-b129-52fedd860245" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 25 05 PM" src="https://github.com/user-attachments/assets/fd402bc7-823b-4429-92f9-426dd4650a4e" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 26 00 PM" src="https://github.com/user-attachments/assets/5ff43130-0c9f-41d9-9a2f-0603a0445f7d" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 26 25 PM" src="https://github.com/user-attachments/assets/77a3ce4a-6687-4033-b3e6-662eaeef4571" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 30 02 PM" src="https://github.com/user-attachments/assets/7efbfd16-8cfb-4117-b0f3-18aef649f4cb" />
<img width="1440" height="900" alt="Screenshot 2025-11-05 at 1 39 48 PM" src="https://github.com/user-attachments/assets/67ac7fbf-e442-4f59-a6d1-e28b86b365b5" />
<img width="492" height="382" alt="Screenshot 2025-11-05 at 1 45 07 PM" src="https://github.com/user-attachments/assets/09885dfd-3692-41bb-89e3-1f814fd40bfa" />

<p> 
<img width="491" height="380" alt="Screenshot 2025-11-05 at 1 45 24 PM" src="https://github.com/user-attachments/assets/82be9678-42e4-4409-911a-cb3bfd414799" />

</p>


<img width="490" height="381" alt="Screenshot 2025-11-05 at 1 45 54 PM" src="https://github.com/user-attachments/assets/292b5a71-e405-4a68-99e8-4d3cd17d12dc" />

<p>
<img width="489" height="380" alt="Screenshot 2025-11-05 at 1 46 24 PM" src="https://github.com/user-attachments/assets/45fe2933-f479-4ec2-bd6f-9e9a52770b21" />

</p>
<img width="491" height="381" alt="Screenshot 2025-11-05 at 1 46 56 PM" src="https://github.com/user-attachments/assets/37d2a034-7f72-4dfc-9392-b84dc5eca558" />

<p>
<img width="494" height="374" alt="Screenshot 2025-11-05 at 1 47 13 PM" src="https://github.com/user-attachments/assets/51baa160-af8c-4ed6-95b9-c6d4d208ca1d" />

</p>
<img width="494" height="379" alt="Screenshot 2025-11-05 at 1 47 36 PM" src="https://github.com/user-attachments/assets/e6f25384-e6f5-464a-b77e-ac351d683cc8" />

<p>
<img width="495" height="379" alt="Screenshot 2025-11-05 at 1 48 02 PM" src="https://github.com/user-attachments/assets/fff6b9a8-8703-4bb8-a6b1-348b9a4a1441" />
  
</p>
<img width="495" height="374" alt="Screenshot 2025-11-05 at 1 53 19 PM" src="https://github.com/user-attachments/assets/5d3027d2-68fc-4823-ad62-9801c1814b96" />

<p>
<img width="495" height="375" alt="Screenshot 2025-11-05 at 1 53 42 PM" src="https://github.com/user-attachments/assets/59d15989-839b-408b-bf30-0c7c2b094453" />
  
</p>
<img width="496" height="374" alt="Screenshot 2025-11-05 at 1 54 38 PM" src="https://github.com/user-attachments/assets/6b92e71b-31d0-4ddb-b6c7-b92ce22435be" />
<img width="770" height="775" alt="Screenshot 2025-11-05 at 1 58 31 PM" src="https://github.com/user-attachments/assets/bbea5365-9757-4b0d-b6f3-2464008c921b" />
<img width="1061" height="599" alt="Screenshot 2025-11-05 at 2 01 22 PM" src="https://github.com/user-attachments/assets/52522aa0-6c5a-475c-ae2d-27c99d81b03a" />
<img width="855" height="467" alt="Screenshot 2025-11-05 at 2 02 37 PM" src="https://github.com/user-attachments/assets/044c0574-2341-45e5-af77-7338baf4f70a" />
<img width="502" height="214" alt="Screenshot 2025-11-05 at 2 03 15 PM" src="https://github.com/user-attachments/assets/131058af-a0f0-44e8-a103-db8579889057" />
<img width="694" height="460" alt="Screenshot 2025-11-05 at 2 04 57 PM" src="https://github.com/user-attachments/assets/60a21bc5-5916-4803-aa7b-c8ab36996b72" />
<img width="697" height="461" alt="Screenshot 2025-11-05 at 2 06 46 PM" src="https://github.com/user-attachments/assets/e67d7650-8c0f-498b-a7e9-20a06d54ddbf" />
<img width="502" height="213" alt="Screenshot 2025-11-05 at 2 07 18 PM" src="https://github.com/user-attachments/assets/6659fef5-4555-4d43-9ab5-828e23576164" />

<p>
<img width="1433" height="343" alt="Screenshot 2026-02-03 at 12 22 33 PM" src="https://github.com/user-attachments/assets/2ba2d8c0-9f35-4073-90fc-7755ab414d57" />
  
</p>
<img width="613" height="299" alt="Screenshot 2025-11-05 at 2 12 34 PM" src="https://github.com/user-attachments/assets/59b319e0-fbcf-4484-95b9-507fdb783555" />
<img width="608" height="446" alt="Screenshot 2025-11-05 at 2 13 34 PM" src="https://github.com/user-attachments/assets/fedbb361-faa5-421f-90d8-7bbdc113619f" />
<img width="1433" height="343" alt="Screenshot 2026-02-03 at 12 22 33 PM" src="https://github.com/user-attachments/assets/8f611a62-60aa-4511-94d9-10d087e899c2" />
<img width="1063" height="547" alt="Screenshot 2025-11-05 at 4 19 23 PM" src="https://github.com/user-attachments/assets/98c8dd9f-dee9-43f6-9315-abc6d4b63d1e" />
<img width="702" height="824" alt="Screenshot 2025-11-05 at 4 21 02 PM" src="https://github.com/user-attachments/assets/236121a6-d320-4d0b-82c5-b5b3cbea2081" />
<img width="508" height="816" alt="Screenshot 2025-11-05 at 4 24 46 PM" src="https://github.com/user-attachments/assets/ba3e8069-98c7-473a-850d-0578ad60d122" />
<img width="506" height="698" alt="Screenshot 2025-11-05 at 4 25 21 PM" src="https://github.com/user-attachments/assets/043b20cf-1722-4ad9-a1cc-346a89498c86" />
<p>
  

<img width="352" height="144" alt="Screenshot 2025-11-05 at 4 27 34 PM" src="https://github.com/user-attachments/assets/5adf8791-9f50-4ce4-9c02-b17e3e4fb476" />
</p>
<img width="309" height="132" alt="Screenshot 2025-11-05 at 4 28 09 PM" src="https://github.com/user-attachments/assets/1b0612f9-1674-453b-890f-489ebf3dee74" />
<p>
<img width="573" height="687" alt="Screenshot 2026-02-04 at 2 54 18 PM" src="https://github.com/user-attachments/assets/53100a2a-e661-4422-8e84-88bfe0d0ac9c" />
</p>

<p>
<img width="360" height="414" alt="Screenshot 2025-11-05 at 4 30 15 PM" src="https://github.com/user-attachments/assets/bea5dff6-7dfa-4164-a2d4-7fd4561bda1c" />
</p>

<img width="411" height="802" alt="Screenshot 2025-11-05 at 4 35 34 PM" src="https://github.com/user-attachments/assets/7e816da3-2095-407e-95fb-d902babe015d" />
<p>
<img width="417" height="561" alt="Screenshot 2025-11-05 at 4 36 07 PM" src="https://github.com/user-attachments/assets/64daacf1-c311-4b37-83b0-ab7cd6c64949" />
</p>
<img width="426" height="250" alt="Screenshot 2025-11-05 at 4 36 30 PM" src="https://github.com/user-attachments/assets/4ee84410-98f6-4586-be1f-fc2c6e2029d9" />
<p>

<img width="418" height="323" alt="Screenshot 2025-11-05 at 4 36 49 PM" src="https://github.com/user-attachments/assets/5161de3a-8078-493c-8cd4-5860c684a7db" />
</p>

<img width="403" height="71" alt="Screenshot 2025-11-05 at 4 38 32 PM" src="https://github.com/user-attachments/assets/24205e9a-c0c4-4186-a759-d75e79498763" />
<p>
  <img width="263" height="24" alt="Screenshot 2025-11-05 at 4 39 28 PM" src="https://github.com/user-attachments/assets/1d5bb86d-07fd-4c00-80f0-6ccc0c2fa778" />
</p>
<img width="435" height="133" alt="Screenshot 2025-11-05 at 4 40 18 PM" src="https://github.com/user-attachments/assets/e917dcfe-38cc-4b65-aee6-2af74b5d319f" />

<p>
<img width="400" height="501" alt="Screenshot 2025-11-05 at 4 40 50 PM" src="https://github.com/user-attachments/assets/4ee37c58-4a23-426f-85ac-4b48a9a4f627" />
</p>  
<img width="760" height="504" alt="Screenshot 2025-11-05 at 4 41 26 PM" src="https://github.com/user-attachments/assets/b7c063af-b56a-4ed0-8c42-15085b00883b" />
<img width="513" height="268" alt="Screenshot 2025-11-05 at 4 42 25 PM" src="https://github.com/user-attachments/assets/a37ad889-a359-4222-96e5-a06f2782b04a" />
<img width="751" height="515" alt="Screenshot 2025-11-05 at 4 42 48 PM" src="https://github.com/user-attachments/assets/0ab6f12a-b07e-4876-bab0-3941c6d0a7a0" />
<img width="401" height="149" alt="Screenshot 2025-11-05 at 4 43 10 PM" src="https://github.com/user-attachments/assets/6fc4cb6c-d894-4f4e-b963-fe670a1bd1e0" />
<p>
<img width="456" height="282" alt="Screenshot 2025-11-05 at 4 44 34 PM" src="https://github.com/user-attachments/assets/1f99b47b-5fa2-427c-b9dc-c6cb657da004" />
  </p>
  <img width="907" height="585" alt="Screenshot 2025-11-05 at 4 46 12 PM" src="https://github.com/user-attachments/assets/93595a28-d0d8-4462-8710-f60dd8affac1" />
<img width="752" height="509" alt="Screenshot 2025-11-05 at 4 46 40 PM" src="https://github.com/user-attachments/assets/5c9ddb00-d469-4a43-ba2e-4bc33b990e23" />
<img width="396" height="507" alt="Screenshot 2025-11-05 at 4 47 13 PM" src="https://github.com/user-attachments/assets/630016c7-5cb9-4912-8d50-7215fe190e89" />
<img width="710" height="826" alt="Screenshot 2025-11-05 at 4 48 17 PM" src="https://github.com/user-attachments/assets/8377aafe-7871-4039-ab17-729e809dd0eb" />
<img width="705" height="831" alt="Screenshot 2025-11-05 at 4 52 21 PM" src="https://github.com/user-attachments/assets/285cd189-51b8-4ef3-b3a4-cdb230d6e29e" />
<p>
<img width="426" height="193" alt="Screenshot 2025-11-05 at 4 55 43 PM" src="https://github.com/user-attachments/assets/ecb843a0-e599-4598-a5cd-bdfc7f3ca29e" />
  </p>
  <img width="417" height="197" alt="Screenshot 2025-11-05 at 4 56 54 PM" src="https://github.com/user-attachments/assets/6456ca83-3b28-42c7-b82d-0c1754906e95" />
  <p>
<img width="419" height="209" alt="Screenshot 2025-11-05 at 4 57 20 PM" src="https://github.com/user-attachments/assets/45f08506-591b-42bf-b7ad-049522af1555" />
    </p>
    <img width="591" height="459" alt="Screenshot 2025-11-05 at 4 57 45 PM" src="https://github.com/user-attachments/assets/a734267e-80f3-4b16-b4c5-bef60caad096" />
<img width="590" height="462" alt="Screenshot 2025-11-05 at 4 58 02 PM" src="https://github.com/user-attachments/assets/f70b29fa-c5d5-49c2-a674-a5639833b47b" />
<img width="592" height="456" alt="Screenshot 2025-11-05 at 4 58 19 PM" src="https://github.com/user-attachments/assets/6ff8bc79-1f9e-44b2-8469-d52c50d7fb9e" />
<img width="593" height="460" alt="Screenshot 2025-11-05 at 4 59 16 PM" src="https://github.com/user-attachments/assets/81a04762-e203-4a8a-a2e1-a22f9a0b36d6" />
<img width="594" height="457" alt="Screenshot 2025-11-05 at 4 59 31 PM" src="https://github.com/user-attachments/assets/679a2e98-765b-4cbc-8cb5-03cedb911c30" />
<img width="594" height="458" alt="Screenshot 2025-11-05 at 5 00 00 PM" src="https://github.com/user-attachments/assets/1ec8d80d-9d72-4528-ab12-6bdb48781c05" />
<p>
<img width="378" height="446" alt="Screenshot 2025-11-05 at 5 01 13 PM" src="https://github.com/user-attachments/assets/096c44b2-9a8c-44a4-9809-5688e0210792" />
  </p>
  <img width="674" height="477" alt="Screenshot 2025-11-05 at 6 34 23 PM" src="https://github.com/user-attachments/assets/2c6c7769-75f0-4b4c-861a-fe5434e8ee3a" />
<img width="674" height="474" alt="Screenshot 2025-11-05 at 6 35 01 PM" src="https://github.com/user-attachments/assets/a20a8274-838b-43a6-ba2f-b8b7c6be1036" />
<img width="932" height="588" alt="Screenshot 2025-11-05 at 6 35 56 PM" src="https://github.com/user-attachments/assets/db8b1fe1-f25b-4d5c-8b9d-0e51112aade4" />
<img width="312" height="254" alt="Screenshot 2025-11-05 at 6 36 31 PM" src="https://github.com/user-attachments/assets/3a64abd1-c324-40ba-99b0-fab0b6974c17" />
<p>
<img width="689" height="368" alt="Screenshot 2025-11-05 at 7 44 00 PM" src="https://github.com/user-attachments/assets/92e125ca-07f9-43bf-b46a-1c3f955969a7" />
  </p>
  <img width="611" height="636" alt="Screenshot 2025-11-05 at 7 45 19 PM" src="https://github.com/user-attachments/assets/13e129d2-bb27-48e2-ae72-47ad4a3dcc76" />
  





  
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


