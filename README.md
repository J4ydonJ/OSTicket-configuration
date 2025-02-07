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

- Roles
- Departments
- Agents
- SLA
- Help topic

<h2>Configuration Steps</h2>



![image](https://github.com/user-attachments/assets/58c134cf-81c5-4f88-a53c-abac7fd325ed)



<p>



</p>
<p> 

Setting up <b/>Roles</b>  inside of osTicket allows you to setup specific roles for the agents working inside of your osTicket. There are different roles that are used for different agents. Some agents might be set to view only while other agents can create, delete, merge, etc. You can make your own roles with specific rules that you want for the agents. 


<b/>The Department</b> section will help group up specific agents together that specialize in the same branch of Information Technology. For example, setting up a group of agents that all work within the Sys admin job title will help organize them in osTicket. Setting up Teams within osTicket is similar to groups. Teams are used to get people from multiple departments to be able to work and resolve certain tickets. 


<b/>Agents</b> are made as the employees that work on tickets and solve other issues within osTicket. Agents can be given specific roles and can work on specific tickets given to them.
</p>
<br />

![image](https://github.com/user-attachments/assets/10127b90-e034-4196-9cb5-a33e88516ca6)

<p>

</p>
<p>
<b/>SLA</b> or Service Level Agreements are used to organize the severity of the tickets. Each ticket is placed into a SLA category depending on how much the problem is impacting the business. The picture above shows 3 different categories for the severity of tickets. The Sev-A category shows a 1 hour grace period, which means that the issue is important and needs to be resolved at with a higher priorty. Sev-B has a 4 hour grace period and should be looked at after Sev-A. Sev-C has the longest time at 8 hours and should be focused on last. 
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/81ca6d37-6312-479d-977a-994a10a9f8f8)


</p>
<p>
<b/>Help Topics</b> are used to help determine which category of SLA the ticket needs to be put in. Each help topic has it's own set of priorities that agents can use to help asign the correct people for the problem. The most common help topics are , Business outages, personal computer issues, equipment request, and password resets.
</p>
<br />
