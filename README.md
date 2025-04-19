<h1> Group Policy Additions and Restrictions </h1>

<h2>Description</h2>
This project involves configuring and applying various Group Policy settings within a Windows Server environment to enforce security and system configuration policies. The process began by starting the virtual machine (VM) and accessing Group Policy Management, where a new Group Policy Object (GPO), named "Group Policy," was created and linked to the Tri-Arrow Printing domain. Several security settings were configured, including setting the Interactive Logon: Machine inactivity limit to 600 seconds (10 minutes) and enabling the Desktop Wallpaper policy with the company logo. A Computer Usage Policy was added as the login message for users. Password policies were then enforced, with the Enforce password history set for 12 months, Maximum password age set to 90 days, and Password complexity requirements enabled with a minimum length of 8 characters. Additional system access restrictions were applied, including preventing access to the command prompt (while allowing PowerShell access), enabling the Run menu on the Start Menu, and restricting user access to the Control Panel and PC settings. This project demonstrates the application of Group Policy settings to ensure both security and efficient system management in a Windows Server environment.
<br />

<h2>Languages and Utilities Used</h2>

- <b> Group Policy Managment Console </b> 
- <b> Powershell </b>
- <b> Server Manager </b>
- <b> Group Policy Editor </b>

<h2>Environments Used </h2>

- <b> WIndows Server 2019 </b>

<h2>Project walk-through:</h2>
<p align="left">
Documented the successful completion of the Active Directory installation selection process, <br/> confirming that all necessary components were properly configured for domain services <br/> deployment. <br/><br/>
  <img src="Screenshot 2025-04-17 202325.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
