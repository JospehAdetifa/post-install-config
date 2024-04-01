# post-install-config
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

STEP 1: Configure Roles

Login To Your Osticket VM and go to this website: http://localhost/osTicket/scp/login.php  
Then Login using the previous creditionals you made during the installation phase. 

Go to the Admin Panel 


Click Agents 


Then Click on the Roles tab


Now we want to create a new role so we will click the  "add new role" button

We are going to create an admin role. I will call this Admin role "Supreme Admin".


Next we will click over to the Permissions tab.


Since this is an admin role we will be clicking all of the boxes to grant these types of users full control over the osticket server. Once this is done click add role. 

STEP 2: Configure Departments

Click on the departments tab

Then click "add a new department.

We are going to create a new top level department and we will call it "system administrators"
I don't want to change too much here so we can just configre this department with the default settings. 

Scroll to the bottom and click create dept. 

STEP 3: Configure Teams

Now click the teams tab

Then click add new team

We will call this team Level 2 support.


We can then click the memeber tab to add a user to this team. 


Once this is done click create team to finish.

STEP 4: Configure Ticket Creation 

In the admin panel click settings. 


Then go to users. Once on the users tab. 
Ensure that in the registration method section that anyone can register. Then save changes.

STEP 5: Configure Agents. 

We are going to create some agents in our osticket server. Think of the agents as pretend helpdesk professionals. 

Click on the agents tab.

Then click on add new agents. 

We are going to create two new agents. A male called Jane Doe and a female John Doe. 
The key thing to note is ensure you remember the password by keeping it simple. Remember this is just a lab. 

When Creating the password. Uncheck the box "send the agent a password reset email". 

Create a memorable password then click set. 

Now we are going to give attributes to this user by configuring the other tabs within this agents profile. 
Click on the access tab.

We are going to change Jane's role to supreme admin. 

Next we will look inside team tab and add Jane to the level 2 support.

We will repeat the same process for John but instead he will be in the support department with a view only role. Click create once this is done.

STEP 6: Configure Users

We will be configuring the users next. These are the customers that we are providing support to. 

First we will go to the agents panel at the top. 

Then we can click the user tab. 

Click Add user and fill out thier information. 

We will repeat this same process but this time we will make a male user called Ken. 

STEP 7: Configure SLA's 

SLA's are service level agreements. In osTicket the SLA's are time limit targets for tickets. We are going to make 3 levels of SLA's. Sev A, B and C. With each letter decreasing the level of severity. 

Go back to the admin panel at the top. 

Hover over the manage tab then click SLA.

Then click add a new SLA Plan. 

Our SLAs will be as follows. 
Sev-A 1 hour,24/7
Sev-B 4 hours,24/7
Sec-C 8 hours,8 hours during business hours

Name each of these, use the schedule section to set the time limit to 24/7 or 24/5 etc. 

Then When Finished click Add Plan. 

STEP 8: Configure Help Topics 

Click the help topics tab at the top 

We will add the following Topics: 
Business Critical Outage 
Personal Computer Issues 
Equipment Request 
Password Reset

To do this click add new topic. Fill out the name then save changes. 

With all of the done the post-installion of osTicket is finished.



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
