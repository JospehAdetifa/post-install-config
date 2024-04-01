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

Login To Your osTicket VM and go to this website: http://localhost/osTicket/scp/login.php  
Then Login using the previous creditionals you made during the installation phase. 
Go to the Admin Panel 

<img width="1000" alt="Screenshot 2024-04-01 at 14 20 29" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/b661b107-92e4-44cc-b341-8647e04d8358">


Click Agents 


<img width="1000" alt="Screenshot 2024-04-01 at 14 21 01" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/d71a78d6-d0e3-49e6-aee2-c7a33566a706">


Then Click on the Roles tab


<img width="1000" alt="Screenshot 2024-04-01 at 14 21 38" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/980e8c1f-6672-4a0f-b3e8-c901ac3f3aed">


Now we want to create a new role so we will click the  "add new role" button


<img width="1000" alt="Screenshot 2024-04-01 at 14 24 17" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/1cb5446b-15b2-4061-b95a-e9a8e91259f6">


We are going to create an admin role. I will call this Admin role "Supreme Admin".


<img width="624" alt="Screenshot 2024-04-01 at 14 26 20" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/7f125c40-b6fb-41f3-a307-f34318785255">


Next we will click over to the Permissions tab.


<img width="975" alt="Screenshot 2024-04-01 at 14 30 15" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/771ad649-5fc3-4c04-b500-4dcdab2fa426">


Since this is an admin role we will be clicking all of the boxes to grant these types of users full control over the osTicket server. Once this is done click add role. 


<img width="975" alt="Screenshot 2024-04-01 at 14 31 43" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/f1f6b1b8-41e6-4d0b-a2d8-3d7f5f355a78">


STEP 2: Configure Departments


Click on the departments tab



Then click "add a new department.


<img width="342" alt="Screenshot 2024-04-01 at 14 32 28" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/ffafa1e2-c91c-442a-bcfc-a0491c48162c">


We are going to create a new top level department and we will call it "system administrators"
I don't want to change too much here so we can just configre this department with the default settings. 


<img width="682" alt="Screenshot 2024-04-01 at 14 36 09" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/a1f29fa1-4c49-4da8-8d03-91ebb76257d7">


Scroll to the bottom and click create dept.


<img width="682" alt="Screenshot 2024-04-01 at 14 36 28" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/cb34affb-7082-40e4-8c3d-e0f7c480ccb3">


STEP 3: Configure Teams


Now click the teams tab


<img width="682" alt="Screenshot 2024-04-01 at 14 38 52" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/f1c10071-9dca-46d5-900c-283d7ab90d16">


Then click add new team


<img width="950" alt="Screenshot 2024-04-01 at 14 40 05" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/97d5d252-5664-4f4a-a368-c287a9b7bf77">


We will call this team Level 2 support.


<img width="955" alt="Screenshot 2024-04-01 at 14 49 10" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/b0285e14-dbdb-4463-bda0-f5be3fe21bce">


We can then click the memeber tab to add a user to this team. 


<img width="261" alt="Screenshot 2024-04-01 at 14 49 36" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/9baf1835-4150-4f61-8be7-2803ba99adba">


<img width="458" alt="Screenshot 2024-04-01 at 14 49 59" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/d697d15d-f35c-4d61-8aa2-9eb92a2643e0">


Once this is done click create team to finish.


<img width="712" alt="Screenshot 2024-04-01 at 14 50 16" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/b9517ee6-267f-40f9-8714-a56bf0cf548d">


STEP 4: Configure Ticket Creation 

In the admin panel click settings. 


<img width="716" alt="Screenshot 2024-04-01 at 14 53 04" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/535bb0a1-0e7d-4ba5-a695-411545457e1e">


Then go to users. Once on the users tab. 
Ensure that in the registration method section that anyone can register. Then save changes.

STEP 5: Configure Agents. 

We are going to create some agents in our osTicket server. Think of the agents as pretend helpdesk professionals. 

Click on the agents tab.


<img width="807" alt="Screenshot 2024-04-01 at 14 59 35" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/c4ae72c5-8878-47a1-8e5e-f795c95ba510">


Then click on add new agents. 


<img width="259" alt="Screenshot 2024-04-01 at 15 04 24" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/70c3adf3-16f4-4dab-9e23-d9a6cd7be8ea">


We are going to create two new agents. A female called Jane Doe and a male John Doe. 
The key thing to note is ensure you remember the password by keeping it simple. Remember this is just a lab. 


<img width="957" alt="Screenshot 2024-04-01 at 15 07 40" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/12bc43ad-ecf4-4780-ba7f-cc46f27c14c1">


When Creating the password. Uncheck the box "send the agent a password reset email". 


<img width="649" alt="Screenshot 2024-04-01 at 15 10 34" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/def1649f-eeb3-4a94-9e83-b50f7216f735">


Create a memorable password then click set. 


<img width="651" alt="Screenshot 2024-04-01 at 15 11 26" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/8df9e674-5ea8-4cdf-88ee-9c7e903ce023">


Now we are going to give attributes to this user by configuring the other tabs within this agents profile. 
Click on the access tab.


<img width="647" alt="Screenshot 2024-04-01 at 15 13 43" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/9bac41aa-2ccd-4c4a-a7ce-f9482a197ba9">


We are going to change Jane's role to supreme admin. 


<img width="959" alt="Screenshot 2024-04-01 at 15 20 40" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/81864357-e0b2-4442-a8cc-09f97346d64b">


Next we will look inside team tab and add Jane to the level 2 support.


<img width="959" alt="Screenshot 2024-04-01 at 15 22 19" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/2606bf25-c0da-4e27-8421-aa904214eec0">


We will repeat the same process for John but instead he will be in the support department with a view only role. Click create once this is done.


<img width="959" alt="Screenshot 2024-04-01 at 15 28 30" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/e0bf39d9-0d4f-4d06-a719-75d8a4995249">


STEP 6: Configure Users

We will be configuring the users next. These are the customers that we are providing support to. 

First we will go to the agents panel at the top. 


<img width="954" alt="Screenshot 2024-04-01 at 15 32 05" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/015c1d07-1a03-41bc-b069-e761be520a03">


Then we can click the user tab. 


<img width="954" alt="Screenshot 2024-04-01 at 15 32 45" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/9b0dc992-97b5-4022-872a-0abb124dd2ce">


Click Add user and fill out thier information. 


<img width="954" alt="Screenshot 2024-04-01 at 15 34 04" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/5c4b1040-9f65-4f22-aff2-56562e11e3b8">


<img width="650" alt="Screenshot 2024-04-01 at 15 35 24" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/a85adb38-d7a0-4384-ba53-615f9367816a">


<img width="957" alt="Screenshot 2024-04-01 at 15 35 58" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/47654c52-1d9c-4ac6-a1f6-3d3061655fc7">


We will repeat this same process but this time we will make a male user called Ken. 


<img width="957" alt="Screenshot 2024-04-01 at 15 37 33" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/c1421a0c-2418-4954-993a-29053a05e5f0">


STEP 7: Configure SLA's 

SLA's are service level agreements. In osTicket the SLA's are time limit targets for tickets. We are going to make 3 levels of SLA's. Sev A, B and C. With each letter decreasing the level of severity. 

Go back to the admin panel at the top. 


<img width="957" alt="Screenshot 2024-04-01 at 15 42 14" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/637cd1ba-f432-4da7-b38e-633360d3d904">


Hover over the manage tab then click SLA.


<img width="957" alt="Screenshot 2024-04-01 at 15 42 37" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/cde2c827-ceb9-4a3a-b118-8eb32627cbd3">


Then click add a new SLA Plan. 


Our SLAs will be as follows. 
Sev-A 1 hour,24/7
Sev-B 4 hours,24/7
Sec-C 8 hours,8 hours during business hours

Name each of these, use the schedule section to set the time limit to 24/7 or 24/5 etc. 


<img width="956" alt="Screenshot 2024-04-01 at 15 48 09" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/2e0ecea4-7fc3-4f5e-8078-b3ffec16e219">


<img width="956" alt="Screenshot 2024-04-01 at 15 48 09" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/57548b78-fcc2-4e5a-8fed-8414f96b9bc3">


<img width="958" alt="Screenshot 2024-04-01 at 15 49 32" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/2bb7337b-5924-4be4-9122-669198b7041e">


Then When Finished click Add Plan. 

STEP 8: Configure Help Topics 

Click the help topics tab at the top 


<img width="960" alt="Screenshot 2024-04-01 at 15 50 35" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/8985646e-5005-4571-9792-8dba34cf794c">


We will add the following Topics: 
Business Critical Outage 
Personal Computer Issues 
Equipment Request 
Password Reset

To do this click add new topic. Fill out the name then save changes. 


<img width="960" alt="Screenshot 2024-04-01 at 15 54 59" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/2bd50d85-8352-4eab-886a-3730150cd85d">


<img width="959" alt="Screenshot 2024-04-01 at 15 55 50" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/3f5f62f8-c37a-4fcd-8dc5-7d4143cc183c">


<img width="959" alt="Screenshot 2024-04-01 at 15 56 24" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/e171d055-4b4c-46ae-a610-4b5c3e5ac00a">


<img width="959" alt="Screenshot 2024-04-01 at 15 56 59" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/e0da2a66-6b1e-451b-9dad-b799220eda16">


<img width="959" alt="Screenshot 2024-04-01 at 15 57 24" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/e3929278-5a50-4b8f-93ee-1ed82f9d3c88">


<img width="959" alt="Screenshot 2024-04-01 at 15 58 29" src="https://github.com/JospehAdetifa/post-install-config/assets/165278529/08860cd3-e1eb-4e3f-add1-b41ac2d9445f">


With all of the done the post-installion of osTicket is finished.


