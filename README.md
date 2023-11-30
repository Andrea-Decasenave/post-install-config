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

- Gain a good understanding of all different parts of the Osticket system
- Configuring and assigning roles 
- Confuguring and creating Departments
- Creating Agents,Teams, and Users
- Creating and assigning tickets
- Configuring (SLA) Service Level Agreements wiht in the ticketing system
- Creating Help Topics

<h2>Configuration Steps</h2>

  **Configuring roles**
 
  
  **IMPORTANT**- OsTicket has two panels "Admin panel" and "Agent panel". For this lab we will be using the "Admin panel" you will know wwhich one you are on beccause the opposite name will show on top.  
</p>

**Roles**- are the permissions granted to Agents per Department that they have access to.

![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/d9d9dfb9-714c-4927-b425-c69b880659fe)

(You can see the top says Agent panel meaning that we are currently in the Admin panel)

- On the Admin panel go to the Agents tab then click on Roles and **Add New Role**
- Name the role **Supreme Admin**
- On the premissions tab ( here you add soecific permissions to a role) select all presmissions under all 3 cateogries then click **Add Role**
  ![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/711ddfc9-a8d2-4903-9b2a-449d68736a59)

 <h2>Creating Departments</h2>
 
**Department**- Departments systematically address tickets in accordance with their respective levels of importance or special instructions.

 - Still on the admin panel and agent tab click on the department  and click **Add New Department**
 -  Name the department **System Administrator** and leave everything else as defaulr and click **Create Department**
  ![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/5509abd4-ca72-4d64-8912-d311eade72bc)
 
<p> 
</p>
<h2>Creating Teams</h2>

**Teams**-group of agents from different Departments and organize them to handle a specific problems or users via a Help Topic or Ticket Filter.

- Still on the Agent tab click on "Teams" name it ** Level II Support
- Then head to the members tab and make yourself a member and finally click **create team** 

<h2>Creating Agent</h2>

**Agents**/Workers- have access to the help desk, enabling them to promptly respond to and resolve tickets.
( for this section we are going to add 2 new agents)

- On the agent tab click on "Agents" then **Add New Agent**
- Then create a name it can be any name but I will be using "Jane Doe" and i will also create and email address ex: **jane.doe@osticket.com**
- set the user name as jane.doe (Write this down on note pad)
- Click set password and make the password **Password1** and uncheck the boxes above and bellow 
  ![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/5a811f03-ce67-49ba-99f4-f7b7c1b7830f)

  
![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/e53592a5-65dc-4c9a-905d-925f414edc98)

- On the acess tab make her Primary Department: **System Administrator** and **Supreme Admin**
  ![image](https://github.com/Andrea-Decasenave/post-install-config/assets/150068516/ab09ff16-d7ec-4fe5-a792-060eaf042c49)
- On the permissions tab make sure all permisions are checked snd on the teams tab make her oart of level II team 
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
