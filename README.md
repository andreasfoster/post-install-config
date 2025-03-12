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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure SLA
- Configure Help topics 

<h2>Configure Roles</h2>

<p>
<p>
We'll be configuring a supereme admin role, Once youv'e signed into osTicket press admin panel, go to agents at the end and press add new role. Put supreme role in name box and give the role all permissions by clicking every single box. 

 
</p>
<br />



<h2>Configure Departments</h2>

<p>
<p>
We'll be configuring a SysAdmin department, press departments and create new department. Once it asks for name type SysAdmin and create the department. 

 
</p>
<br />


<h2>Configure Teams</h2>

<p>
<p>
We'll be configuring a Online Banking Tean, press teams and create new team, Once it asks for name type Online Banking and create the team. 

 
</p>
<br />


<h2>Allow anyone to create tickets</h2>

<p>
<p>
While in the admin panel press settings, go to users and then uncheck (require registration and login to create tickets) 

 
</p>
<br />


<h2>Configre Workers</h2>

<p>
<p>
While in the admin panel press agents and press add new. Once youre here create two random individuals and assign one of them to the supreme admin role and the other to any role of your choosing and also assign them two two different teams. The phone number nor email address needs to be real but make sure to keep track of the info incase osTicket requires it from you. 

 
</p>
<br />


<h2>Configre SLA</h2>

<p>
<p>
While in the admin panel go to manage and then SLA. Create 3 SLAs, an SLA for Sev A (1 hour Grace Period 24/7 schedule), for Sev B (4 hour Grace Period 24/7 schedule) and for Sev C (8 hour Grace Period Mon-Fri 8-5pm schedule).  

 
</p>
<br />


<h2>Configre Help Topics</h2>

<p>
<p>
While in the admin panel go to manage and then help topics. Once you're there create all 5 topics down below and pick the parent topic that you feel best suites it. 
  
- Buisness Critical Outage
  
- Personal Computer Issues

- Equipment Request

- Password Reset 

- Other
 
</p>
<br />


