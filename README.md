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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="1434" height="828" alt="VM Creation" src="https://github.com/user-attachments/assets/10e2f3eb-da2e-401d-81ff-f46fe835e8a6" />
/>
</p>
<p>
Here is the finish product of an osTicket Resource group which contains a virtual machine. The virtual machine allows me to access a Windows Pro 11 OS on a remote desktop. On the remote desktop I have executed an extensive installation of osTicket and this will be the post installation configuration.
</p>
<br />

<p>
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/9735c95f-4618-4b41-bdc4-f26f7609bb9d" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/182eb70a-0a75-4bbc-b5e8-ac2880b90de6" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/0f733ed0-c364-4cc6-a480-ed861faacd27" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/6f6e6b0e-c801-42a9-97f2-8e7690ef894d" />

</p>
<p>
Apart of the configuration of the installation is creating roles, agents, departments, and teams. In the screenshot above, you can see I created roles which essentially just gives agents different levels of access. I also created agents to distribute the roles to and then assigned each agent to a department and a team in which I also created.
</p>
<br />

<p>
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/6a4fe6cb-cf50-4e5f-bd72-e37e86712c92" />
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/e4cce4ef-e882-4775-ae82-38276cc266dc" />


</p>
<p>
Service-Level Agreements are basically a promise between provider and consumer on what level of service you will provide. In terms of IT, it is the response and priority level of certain tickets. In the screenshots above you will see I created a Sev-A, Sev-B, and Sev-C. Each one is a different severity level. Sev-A is high severity and needs to be responded to within an hour of receiving. Sev-B is moderate severity and gives you a 4 hour grace period to respond. Sev-C is lowest severity and gives you an 8 hour grace period and also only has to be responde to during business hours
</p>
<br />
