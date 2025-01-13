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

- Adding and configuring new Role, Department etc.
- Create SLA's for tickets.
- Enable End Users for Ticket Creation.

<h2>Configuration Steps</h2>

<p>
  
![New Role   Configed](https://github.com/user-attachments/assets/32e2c243-a267-4a85-8ba1-f27e3e941e68)

</p>
<p>
  
![Adding and Configed New Dept](https://github.com/user-attachments/assets/78c69574-9ea9-4796-869f-d647453fd127)

</p>
<p>
Within the osTicket system, logging using admin credentials. Now you may navigate the dashboard into "agents" where you may add agents/teams/roles/department and configure the settings for each one as well as give access to who you choose to.
</p>
<br />


<p>
  
![SLA config   creation](https://github.com/user-attachments/assets/6e25a936-4d5e-4d4b-88c5-a8c8a0a643cf)

</p>
<p>
Here we create some "Service-Level Agreements." This will be used for when tickets are created we have a procedure in place for resolving the tickets including which will have priority. 
</p>
<br />


<p>
  
![End User tickets](https://github.com/user-attachments/assets/48ebb55e-fff3-4c08-9cb9-38c81a6fff12)

</p>
<p>
Next we must ensure that the back-end users are able to create tickets without being forced to register (unless otherwise desired for them to register). We do this by making sure the "Registration required" box is unchecked.
</p>
<br />
