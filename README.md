
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

<h2>Configuration Steps</h2>

1.) If you have not already installed osTicket start here: https://github.com/JacobKnittle/osticket-prerequisites

2.) You can use these links to log in as an admin http://localhost/osTicket/scp/login.php or End Users osTicket URL: http://localhost/osTicket/. Log in using the admin name and password you created during installation.
<p>
<img width="680" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/f3c14111-359f-475c-8024-1e1d5f66e96f">
</p>

3.) This should be your screen starting point for this section.

<p>
  <img width="388" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/7c60fae3-f52b-478c-9c15-59e70e06fa42">
</p>

4.) From there you want to navigate to Admin Panel -> Agents -> Roles -> Add New Role. Under definition, name the role Supreme Admin and permissions select all the permissions in each section and then add the role.
<p>
  
<img width="385" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/5c439094-dcc3-4a92-9fa4-58de1e170ee0">
</p>

<p>
  <img width="388" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/71c8a1b5-827d-4a52-94b3-5249a8829cd4">

</p>

5.) Make sure you are still in Admin Panel -> agents -> then navigate to departments. Select add new department and name it System Administrators then create the department.

<img width="355" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/355fb950-dfe7-4329-b0c6-bc4575752e00">

6.) Next while still in the Agents tab move to Teams -> Add Team -> put the Name as: "Level II Support" and save the changes.

7.) Proceed to the Settings tab -> User Settings -> and uncheck require registration so that anyone can make anonymous tickets and save changes.

<p>
  <img width="484" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/d89a0f8b-3da2-48c0-bad9-4cd3ab223c74">

</p>

8.) Next we are going to the agents (workers for handling tickets) so proceed to the Agents tab. We will then add two new agents Jane and John by selecting Add New Agent and filling in the name, email, username, and select Set Password to make a password (deselect require password change and remember this info like always). Switch to the Access tab put them under System Administrators and Supreme Admin and Level II Support under the teams tab. Now you can create your Agent.

<p>
  <img width="488" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/425133f7-9f35-4f9b-add6-7eedfecdcb8e">

</p>

<p>
  <img width="487" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/f6fb971a-3ce4-49fa-a201-3387ad4b6225">

</p>

<p>
  <img width="486" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/daf8e638-7b55-49be-bda3-f45165c0091f">

</p>

9.) We will now go to the Agent Panel at the top and create some users. Select Add User then fill out the email address and full name then click Add User.

<p>
  
<img width="488" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/daa17cb6-a84d-4c27-a129-d14fde717344">
</p>

10.) Now return the Admin Panel -> Manage -> SLA. We are going to create three SLAs that show different priority plans for tickets that we create. Select Add New SLA Plan and make three SLAs including Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours).

<p>
  <img width="484" alt="image" src="https://github.com/JacobKnittle/osTicket-Post-Install-Config/assets/124555008/40759fa1-2674-45b2-8633-ded30b49e359">

</p>


