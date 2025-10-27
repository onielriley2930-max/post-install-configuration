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
Next we would create departments. Departments organize where tickets go. Departments represent divisions or categories of your organization that handle different kinds of tickets.
Each department can have its own settings, agents, email addresses, and permissions.

 Example
	-	Customer Service
	-	Technical Support
	-	Billing Department
	-	Human Resources

 Importance of Departments
		Ticket Routing: Incoming tickets are automatically directed to the correct department (e.g., a billing issue → Billing Department).
		Organization: Keeps tickets sorted by subject area, avoiding confusion or mix-ups.
		Custom Rules: Each department can have unique autoresponders, signatures, SLA plans, and email addresses.
		Privacy & Access Control: Tickets in one department can be hidden from agents in another, protecting sensitive information.
</p>
<br />

<p>
<img src="https://imgur.com/VxPVxoy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Department is created we now create Teams. Teams group agents who can work across departments.
	 Example

A “Priority Response Team” may include agents from both Customer Service and Technical Support who handle high-priority issues together.

🎯 Importance of Teams
	1.	Collaboration: Allows agents from different departments to handle tickets together.
	2.	Flexibility: You can assign tickets to a team even if no single department applies.
	3.	Backup Coverage: If one department is overloaded, a team can help share the workload.
	4.	Project-Based Assignments: Ideal for short-term campaigns or special clients (e.g., “Rebel Salute Event Support Team”).
</p>
<br />
<img src="https://imgur.com/mEMwPVR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we would create Agents, aslo known as Workers. Agents are your internal support staff — the people who log into the Staff Control Panel to view, respond to, and manage tickets.
🎯 Importance of Agents
	1.	Ticket Handling: They are the front line — reading, replying, and resolving customer tickets.
	2.	Accountability: osTicket tracks which agent worked on which ticket, ensuring transparency.
	3.	Workflow Control: Agents can reassign, escalate, or close tickets based on their role permissions.
	4.	Performance Tracking: Reports and analytics show each agent’s response time and ticket resolution rate.

</p>
<br />
<img src="https://imgur.com/W2ErXaF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
And finally End Users. Users are the end customers or clients who submit tickets when they need help.
They access the Client Portal (front-end) — not the staff panel. 💡 Example
	•	A customer sending an email to support@yourcompany.com
	•	A visitor filling out your “Contact Us” form on the osTicket web portal

🎯 Importance of Users
	1.	Ticket Creation: Every issue starts with a user’s submission — via email, form, or API.
	2.	Communication: Users receive automatic replies, updates, and resolutions from agents.
	3.	Customer History: osTicket stores all tickets by user, helping agents review past issues quickly.
	4.	Self-Service Support: Users can search FAQs and knowledge base articles to resolve common problems without opening a ticket.
</p>
<br />
Real-World Example (osTicket in Action)

Let’s say your company runs Melanin Bliss Holistic Support Desk:
	•	A User named Shanice sends an email: “My package was damaged.”
	•	osTicket auto-routes it to the Customer Service Department.
	•	The ticket is assigned to Agent Oniel who has the “Agent” role.
	•	Because it’s a priority case, the “Refund Response Team” (cross-department) is added to assist.
	•	The ticket is resolved, and Shanice receives an email confirmation.

That’s osTicket’s structure working perfectly.
