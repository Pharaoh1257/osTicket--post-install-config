<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents(workers)
- Configure Users(customers)
- Configure SLA(Service-level Agreements)


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/uxeMwH4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the osTicket portal, go to the agent panel, then click roles (grouping and giving permissions) and you will see the agents tab then click roles and you will then see the different levels of access (expanded access, limited access and view only) If all access box is checked, you will grant all permissions to that role. There you can also add a new role, name and add all permissions to specific roles.
</p>
<br />

<p>
<img src="https://i.imgur.com/8Z5cKqz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure departments in osTicket permissions, you can go to the admin tab, then the agents tab, and click departments. There, you can add a new department and configure and assign people in the settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/PbSCiFq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure teams, you can go to the admin panel, agents, and then the teams tab. And then you can create or add a new team, which would consist of people from different departments. For example, at a banking company, you could have helpdesk groups sorting the tickets, and system admins would be in charge of the online banking system. Another setting for end users to create their tickets, go back to the admin panel, settings, then click users, make sure the user registration box is unchecked.
</p>
<br />

<p>
<img src="https://i.imgur.com/6G25wd5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure agents, go to the admin panel, the agents tab, and click add new. Input the agent information and change access permissions, assign departments and the specific team, make a username and passwords, and then create.
</p>
<br />

<p>
<img src="https://i.imgur.com/CAO4Vh8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure users(customers), go to the agent panel, users tab and click add new. Input the customer's email, full name, phone number, status, date created, and date updated. (It's an end user that might create a ticket.) 
</p>
<br />

<p>
<img src="https://i.imgur.com/NEcwzGF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure SLA (Service-level Agreement), which is how much time you have to do a specific task from responding to  and completing a ticket, which can range from 1 hour to 8 hours or however many hours are given in the ticket on a 24/7 schedule. Go to the admin panel, click manage, and then click SLA. Then click add new, set active status, and a grace period to respond on a schedule (usually 24/7). Also, create a topic, choose a topic level (either feedback, general inquiry, report a problem, access issue, or business critical outage), and set it to either public or private type in osTicket. 
</p>
<br />


