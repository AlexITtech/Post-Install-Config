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




![image](https://github.com/user-attachments/assets/fa13876b-cfc3-4499-8e04-44f16846b00a)

4.) Next, go to the Agents tab and click on the “Departments” button. Here, we’ll create a new department, assigning each agent to a department based on their role in the help desk. In this case, we’ll set up a “System Administrators” department. Note that additional configurations—such as Service Level Agreements (SLAs), department managers, and email settings—can also be customized in the Departments tab to align with the operational needs of our help desk.





![image](https://github.com/user-attachments/assets/ddfaa8f7-9086-413a-ae11-792f03fd4b29)





![image](https://github.com/user-attachments/assets/14fb5628-2300-4ebc-961e-38844076f596)

5.) To allow anyone to submit tickets, navigate to Admin Panel > Settings > Users. Uncheck the option labeled “Require registration and login to create tickets.” This setting enables unregistered users—those without an account—to create and submit tickets as needed.



![image](https://github.com/user-attachments/assets/7b9891ba-66ac-4443-8490-e179701d193b)

6.) Before tickets can be processed, we need to set up agents (staff members). To do this, go to Admin Panel > Agents > Add New Agent. Fill in each agent’s details, including name, email address, assigned role, and department. This step creates the agent’s profile and ensures they have the correct permissions and access based on their responsibilities.




![image](https://github.com/user-attachments/assets/385f687d-ac03-4db0-b320-c78ba2643d37)


![image](https://github.com/user-attachments/assets/90933750-e4bf-417c-8ef8-7721735f8c27)

7.) For the purposes of our project, we also need to configure users (customers). To do this, navigate to Agent Panel > Users > User Directory > Add User. Add users such as Karen and Shawn by entering their names and email addresses. This setup allows users to submit and manage their support tickets through the system.



![image](https://github.com/user-attachments/assets/251114a3-99e6-444f-a290-d4a1526d9b92)


8.) To assist users in submitting tickets more efficiently, it’s recommended to configure help topics. Navigate to Admin Panel > Manage > Help Topics. Adding relevant help topics will guide users in categorizing their issues appropriately, ensuring tickets are directed to the correct department or agent.







