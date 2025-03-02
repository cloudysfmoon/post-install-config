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

- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
There are two different links one for the admin/agents, and one for the users. 
<p>
Admin/Agents Login Page:
http://localhost/osTicket/scp/login.php 
<p>
End Users osTicket URL:
http://localhost/osTicket 
<p>
We can give permissions to users and select what the agent is able to have access to. 

![1](https://github.com/user-attachments/assets/4ae2abfb-d239-4c79-a805-97e5cd137e90)
<p>
We can also add more departments in the system. We added a System Admin department. 

![2](https://github.com/user-attachments/assets/81168fce-c228-44a0-8a90-1c3f0513bd1c)
<p>
We can add teams, people in other departments can be part of different teams.

![3](https://github.com/user-attachments/assets/3552d7df-5d42-4b49-a98a-ffdfaa97f124)
<p>
We can update the end user settings, we can uncheck the "Require registration and login to create tickets", the end user won't have to sign up for an account to just submit a ticket.

![4](https://github.com/user-attachments/assets/3372cac1-1191-4997-9d13-6e83b8f4d7a8)
<p>
We can add agents, we will add, Jane Doe, and John Doe, the will be able to work on tickets. 


![5](https://github.com/user-attachments/assets/d83c3bd7-22cd-4f1b-bcd3-b81b903e4422)
<p>
  
![6](https://github.com/user-attachments/assets/68eedf6b-e4ed-4b52-8073-cf6c13a0329d)

<p>
We can add users, we will be adding just one, Karen. 

![7](https://github.com/user-attachments/assets/0848239d-d20b-4c59-85b1-e71b34fbf003)
<p>
We can configure SLA's from the Admin Panel.
<p>
Admin Panel -> Manage -> SLA
<p>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
<p>
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
<p>
Sev-C (Grace Period: 8 hours, Business Hours)
<p>
These are the SLA's we are going to configure, but ofcourse they can be changed or adjusted to needs. 

![8](https://github.com/user-attachments/assets/6c12a9fb-f46b-4fb9-9a17-847b628b760a)
<p>

![9](https://github.com/user-attachments/assets/a7d7300e-485e-4b3a-bc5e-d2cb21891c6c)
<p>

![10](https://github.com/user-attachments/assets/a534a73f-cf99-497a-97f6-86c918951f42)
<p>
Configure Help Topics (For when users create a ticket)
<p>
Admin Panel -> Manage -> Help Topics
 <p>
Business Critical Outage
<p>
Personal Computer Issues
<p>
Equipment Request
<p>
Password Reset
<p>
Other
<p>
These are examples, you can add or remove based on what tickets are subitted by users.

![11](https://github.com/user-attachments/assets/f70367fc-391d-45d3-8247-9087c394a05f)
<p>

![12](https://github.com/user-attachments/assets/7a350ac8-3073-4484-9da9-ea01c1c56de0)
<p>

![13](https://github.com/user-attachments/assets/4f696f13-7f13-4b13-a3d5-9a9e6c60a2c3)
<p>

![14](https://github.com/user-attachments/assets/d461c490-b81b-4864-b3e6-eb686d0c700c)

<br />
