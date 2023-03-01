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

<h2>Configuration Steps</h2>

<p>
Login Pages

- Make sure to have two sites on your browser: osTicket login and the user login.
- http://localhost/osTicket/scp/login.php
- http://localhost/osTicket/

</p>
<p>

<hr>

<p>
Configure Roles

- Login into osTicket and make sure you are on the "Admin" panel. You can check if you are on the "Admin" panel if "Agent Panel" is located to the right of your username.
- Click on "Agents" -> Roles -> "Add New Role"
- Add necessary details like name and check whatever permissions you want on the permissions tab.

</p>
<img src="https://i.imgur.com/3f9s1i3.png" width="80%" alt="roles"/>
</p>

<hr>

<p>
Configure Departments

- On the "Admin" panel, click on "Agents" -> "Departments" -> "Add New Department"
- Create some departments like for "Support" and "System Administrators"

</p>
<p>
<img src="https://i.imgur.com/YLQJvBS.png" height="80%" width="80%" alt="deparment"/>
</p>

<hr>

<p>
Configure Teams
  
- Click on "Agents" -> Teams
- Input details for creating teams, in which having teams would help agents organize tickets better

</p>
<p>
<img src="https://i.imgur.com/XFlJyo9.png" height="80%" width="80%" alt="teams"/>
</p>

<hr>

<p>
Configure Agents
  
- Click on "Agents" -> "Agents" -> "Create New Agent"
- Create agents who will be responsible for to respond and resolve tickets
  
</p>
<p>
<img src="https://i.imgur.com/xWIX67y.png" height="80%" width="80%" alt="agent"/>
</p>

<hr>

<p>
Configure SLA & Help Topics
  
- Click on "Manage" -> "SLA" -> "Add New SLA Plan"
- Input details like a name like "SEV-A" (highest severity or importance)
- For help topics, click on "Help Topics", which is part of "Manage"
- Then add details after clicking "Add New Help Topic"
  
</p>
<p>
<img src="https://i.imgur.com/sckxHtZ.png" height="80%" width="80%" alt="sla"/>
</p>

<hr>

<p>
Configure osTicket
  
- Go to "Settings" -> "Users"
- Check the box to the left of "Require registration and login to create tickets"
  
</p>

<hr>

<p>
Configure Users

- Switch into the "Agent" panel
- Click on "Users" -> "Add User"
- Input options: a user's email address and full name

</p>
<p>
<img src="https://i.imgur.com/Ck91MIi.png" height="80%" width="80%" alt="sla"/>
</p>
