<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Deppartments
- Team
- Agents (Workers)
- Users (Customers)
- Help Topics
- Service Level
- Agreements (SLAs)

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/01062c19-fb80-4108-ac8e-9fb414de3d3e)

1.) With osTicket now successfully set up on our virtual machine, the next step is to configure administrative settings within the system. We'll start by defining roles in the help desk, which will allow us to efficiently manage user access and permissions.





![image](https://github.com/user-attachments/assets/1dcc4cb9-192a-4f52-b905-cc9ebb7c4733)


2.) To set up roles in the help desk, navigate to Admin Panel > Agents > Roles, then click "Add New Role."



![image](https://github.com/user-attachments/assets/bea92f2a-92d1-4aed-b301-f89b961cb3a9)


3.) Next, enter a name for the new role—for example, Supreme Admin. This role will define the responsibilities and access levels assigned to users. Since we're creating a Supreme Admin role, we'll enable all available permissions to grant full administrative privileges.







