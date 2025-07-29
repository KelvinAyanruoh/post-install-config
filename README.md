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

- Acknowledge Agent Panel vs Admin Panel
- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

- Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets

- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)

- Configure Users (customers)
Agent Panel -> Users -> Add New
Karen and
Ken
- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other






- Note that in a ticketing system, we will be navigating between the admin and agent panels as seen below,






<h2>Configuration Steps</h2>

<h2>Acknowledge Agent Panel vs Admin Panel
</h2>

<p>
<img width="1135" height="579" alt="image" src="https://github.com/user-attachments/assets/3b2dbcbe-9a1d-41f4-9c54-9575299e079d" />


</p>
<p>
Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
</p>
<br />
<img width="1244" height="1064" alt="image" src="https://github.com/user-attachments/assets/147310c4-5b87-4c40-988c-a3a00d258062" />


- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
</p>
<br />

<p>
<img width="1021" height="708" alt="image" src="https://github.com/user-attachments/assets/76515c2e-9443-4082-ac7b-a33f0b1aa351" />

</p>
<p>


<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets.
</p>
<br />
<p>
<img width="1015" height="721" alt="image" src="https://github.com/user-attachments/assets/0dd9951a-8449-488c-95ef-cc7ad0dc7133" />

</p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>

<img width="1197" height="991" alt="image" src="https://github.com/user-attachments/assets/97ef5bcf-513d-4a71-865d-ec6a3612b680" />

</p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen and
Ken
</p>
<img width="1067" height="596" alt="image" src="https://github.com/user-attachments/assets/558c4b8e-07f5-4296-9605-c3530c74d8e0" />

</p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<img width="829" height="1024" alt="image" src="https://github.com/user-attachments/assets/723d2888-7d0e-4350-a888-192fbf5dbad6" />

</p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<img width="875" height="1113" alt="image" src="https://github.com/user-attachments/assets/7f67e451-0b68-4fc4-b47a-f8a59dd7c181" />


