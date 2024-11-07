# Configuring osTicket post-installation
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuring osTicket</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create a new role, department, and team inside the Admin Panel of osTicket.
- Create two new agents and assign them to different departments.
- Create two new end-users in the Agent Panel
- Create three new SLA's in the Admin Panel


<h2>Configuration Steps</h2>

<p>

![image](https://github.com/bradgarton13/post-install-config/assets/166873905/838d9f4d-3fbe-47c1-870a-b1ef3af59fd5)

1. Inside the Admin Panel of osTicket I have navigated to Agents > Roles and created a new role known as Supreme Admin.


![image](https://github.com/bradgarton13/post-install-config/assets/166873905/af678a36-c04c-470e-92a3-79149f5db71b)

2. Here I have created a new department by navigating to Agents > Departments inside the Admin Panel. This Department is labeled System administrators.


![image](https://github.com/bradgarton13/post-install-config/assets/166873905/c921a6e6-eff3-427c-9935-7b614fba1060)

3. By navigating to Agents > Teams inside the Admin Panel I have created a new team known as Level 2 Support.

![image](https://github.com/bradgarton13/post-install-config/assets/166873905/8118e0ab-1eca-4c9b-9ef8-990908508768)
![image](https://github.com/bradgarton13/post-install-config/assets/166873905/07b96e49-bf6e-45bc-8bc1-d0358b0b6445)

4. Continuing inside the Admin panel, I've navigated to Agents > Agents and created two new agents Jane and John Doe.
5. Jane will be a system administrator in this case with the Supreme Admin role. John will be placed in the Support department the limited View-only access.


![image](https://github.com/bradgarton13/post-install-config/assets/166873905/5e7498eb-ae76-4b8b-aabc-2531cb46f236)

6. After navigating to the Agent Panel, I have created a view end-users with the names Ken and Karen. They will be used to create and view tickets.

![image](https://github.com/bradgarton13/post-install-config/assets/166873905/10db2b3c-9a5a-46ff-b9d3-277d63127903)

7. Lastly, Ive created a few Service-Level agreements. I've three SLA's that each have differing levels of severity.
8. SEV-A will be for most severe tickets with a grace period of 1 hour and schedule of 24/7, meaning the agents will have to address the ticket within 1 hour of creation on any day/ hour of the week. SEV-B will have a grace period of 4 hours on the same 24/7 schedule, and SEV-C will have a 8 hour grace period with a 24hr/ 5-day schedule.

