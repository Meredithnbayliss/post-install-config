<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Configuration</h1>

In this tutorial, I will outline the post-install configuration of the open-source help desk ticketing system osTicket.

  
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Configure Roles
- Configure Departments
- Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Installation Steps</h2>

In Step 1, We Configure Roles
Admin Panel -> Agents -> Roles
Supreme Admin
<p>
<img src="https://i.imgur.com/3ZEUcGh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/Nkq3oos.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/UvNHJ4w.png" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/z2SvrTb.png" alt="Disk Sanitization Steps"/>
</p>
</p>
<img src="https://i.imgur.com/1SlaERm.png" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
In step 2, We Configure Departments
Admin Panel -> Agents -> Departments
System Administrators
</p>
<br />
<p>
<img src="https://i.imgur.com/icDXd6g.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/aum58CH.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
In step 3, Configure Teams
Admin Panel -> Agents -> Teams
Level I Support
Level II Support
</p>
<br />
<p>
<img src="https://i.imgur.com/8vQw1z6.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/zhdzEmZ.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
In step 4, we Allow anyone to create tickets
Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
</p>
<br />
<p>
<img src="https://i.imgur.com/QZ6X84O.png" alt="Disk Sanitization Steps"/>
</p>
<br />
</p>
<br />
<p
In step 5, Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane
John
</p>
<br />
<p>
<img src="https://i.imgur.com/xryRKQc.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/ZFMXGVG.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/opw5AO3.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
In step 6, Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
</p>
<br />
<p>
<img src="https://i.imgur.com/54jQnge.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/Z6aHr5S.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/MIt60zg.png" alt="Disk Sanitization Steps"/>
</p>
<br />
</p>
<br />
</p>
In step 7, we Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
</p>
<br />
<p>
<img src="https://i.imgur.com/zYUBwaU.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/OozxYVw.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/cnWSIBa.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/gOLXXNF.png" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
</p>
<br />
<p>
In step 8, Configure Help Topics
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
</p>
<br />
<p>
<img src="https://i.imgur.com/uJYayfR.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/OQq9S8Z.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/UyniAOr.png" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://i.imgur.com/RkVavBd.png" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
<p>
<img src="https://i.imgur.com/oclAG4r.png" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
This was a very simplistic scenario of the creation of a ticket by a user, how the ticket is assigned and displays the communication of a ticket between agents; subsequently resulting in a resolution.

There are additional scenarios that can also happen while a ticket is being assessed. A ticket can either be reassigned to a different department, escalated in severeity level, or needs to be both reassigned to a more qualified agent/department to handle the issue, depending on business impacts.

I hope this tutorial helps you understand and have a better general overview of a life-cycle of a ticket. Help desk agents can expect to regularly deal with anywere between 10 to 100 tickets during their day depeneding on the company size.

