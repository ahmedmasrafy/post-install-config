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

- Configure roles for grouping permissions
- Configure departments
- Configure teams
- Configure agents
- Configure users (customers)
- Configure SLA
- Configure Help Topics for when users create a ticket

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/d4oTNJy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now within the virtual machine I created with Azure, I just messed with the roles. Assigned roles to different agents, and added some new roles. 
</p>
<br />

<p>
<img src="https://i.imgur.com/4H9yl6e.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now in departments I just messed around and configured the departments visibilty to see tickets. Furthermore, I created different departments and gave them the ability to only see certain type of tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/hrZDNc2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Teams are a collection of Agents that are not in the same department but need access to a specific ticket to work on. So in this part of the project, I added a new team that I will put Agents into them. Then I would later assign them tickets to work on. 
</p>
<br />

<p>
<img src="https://i.imgur.com/tGWQMIL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now this is where I go ahead and made two agents. Created a username and password for both. Then I assigned them to different departments so later in the project I can assign them different tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/vdnJqtH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then I created a couple users so I can create tickets with them so I would be able to close the tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/YzEmqUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
A Service Level Agreement(SLA), is a plan that specifies how long a help desk admin expects to close a ticket. You can escalate tickets based on their priority. So I went on ahead and created a few SLA plans, created tickets and picked the appropriate SLA plan based on the severity of the problem. 
</p>
<br />

<p>
<img src="https://i.imgur.com/d3IYfe7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Basically Help Topics will determine what department the ticket gets routed to which will then determine which Agents will have access to the ticket.  
</p>
<br />

<p>
<img src="https://i.imgur.com/IHXGy8y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then I went on ahead and made up a few help topics which I used to create new tickets for Agents. 
</p>
<br />
