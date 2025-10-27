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

- Roles
- Department
- Teams
- Agents (workers)
- Users (customer)

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/5cLo70L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
🛡️ 1. Security Hardening

After everything is working, your first concern should be locking down your installation. osTicket is built like a real-world support organization.
Each part — Departments, Teams, Agents, and Users — plays a specific role in how tickets are routed, managed, and resolved. In osTicket we would assigned roles. A role defines what an agent (staff member) is allowed to do within the system.
Think of a role as a set of permissions assigned to agents that determines what actions they can perform — such as viewing, replying, assigning, or deleting tickets.

Roles are different from Departments or Teams:
	
.
</p>
<br />

<p>
<img src="https://imgur.com/ynhQ2qC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we would create departments. Departments organize where tickets go.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Department is created we now create Teams. Teams group agents who can work across departments
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
