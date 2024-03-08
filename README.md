<p align="center">
<img width="521" alt="Screenshot 2024-03-07 185508" src="https://github.com/marcusgumbs/networkfilesandpermissions/assets/162270050/135bcecf-e5d3-48d1-b6ab-1814e9c93fb8">

</p>

<h1>Network File Shares and Permissions</h1>
In this tutorial we share out resources over the network and create file shares to allow read, write, or deny access to individual users or groups<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services



<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Create and test file shares
- Create and test security groups
- Verify acess or denial to file shares


<h2>Actions and Observations</h2>

<p>
<img width="523" alt="Screenshot 2024-03-06 201142" src="https://github.com/marcusgumbs/networkfilesandpermissions/assets/162270050/9a3632a9-8115-4c5f-acc4-5bbe74b3fb14">

</p>
<p>
After creating read-access, write access, no access, and accouting folders I assigned permissions to different domain users and groups.  
</p>
<br />

<p>
<img width="350" alt="Screenshot 2024-03-06 201321" src="https://github.com/marcusgumbs/networkfilesandpermissions/assets/162270050/c7868704-6476-4c0c-84c6-1d38c4f3f47f">

</p>
<p>
From the domain controller (VM) I created a security group called Accountants and gave them read/write access to the accountant folder.
</p>
<br />

<p>
<img width="521" alt="Screenshot 2024-03-06 201452" src="https://github.com/marcusgumbs/networkfilesandpermissions/assets/162270050/fb2260c2-0953-4c40-868f-f41ded10eb2d">

</p>
<p>
Once permissions and access were assigned to different users, I verified if the files were allowed or denied access depending on the credentials of the given user.
</p>
<br />
