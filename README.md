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
- Allow anyone to create tickets
- Configure Agents (employees)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/AuyHQLm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 1: CONFIGURE ROLES</h2>

  - Login to your osTicket
  - Admin Panel --> Agents --> Roles
  - Add a new Role, Name it Supreme Admin
  - Select permissions and check all the boxes (tasks, ticket, knowledgebase)
</p>
<br />

<p>
<img src="https://i.imgur.com/Vwv7E4s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/MANvHbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 2: CONFIGURE DEPARTMENTS</h2>

  - Admin Panel --> Agents --> Departments
  - Create a new Department named System Administrators
</p>
<br />
<br />

<p>
<img src="https://i.imgur.com/KDUGIeb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 3: CONFIGURE TEAMS</h2>

  - Admin Panel --> Agents --> Teams
  - Level I Support
  - Create a Level II Support Team
</p>
<br />

<p>
<img src="https://i.imgur.com/Fg9rF3O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/Fg9rF3O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 4: ALLOW ANYONE TO CREATE TICKETS</h2>

  - Admin Panel --> Agents --> Add New
  - Jane Do - create an account, set a password, make Jane a Supreme Admin, add her to our Level II Support Team. Then Create
  - John Do - create an account, set a passwor, make John a Support View Only. Then Create
</p>
<br />

<p>
<img src="https://i.imgur.com/wDtyF5f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/JJipr6M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 5: CONFIGURE FOR USERS</h2>

  - Agent Panel --> Users --> Add New
  - add new User Karen
  - add new User Ken
</p>
<br />

<p>
<img src="https://i.imgur.com/8PlETvH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/CscCtO6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/pXokl0s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 6: CONFIGURE SLA</h2>

  - Admin Panel --> Manage --> SLA (then add 3 new SLAs plans)
  - Sev-A (1 hour, 24/7)
  - Sev-B (4 hours, 24/7)
  - Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/YKpMsef.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</h2>STEP 7: CONFIGURE HELP TOPICS</h2>

  - Admin Panel --> Manage --> Help Topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
</p>
<br />
