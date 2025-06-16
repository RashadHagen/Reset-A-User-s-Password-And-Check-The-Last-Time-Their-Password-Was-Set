<h1>Active Directory Users and Computers (ADUC) - Reset A User’s Password And Check The Last Time Their Password Was Set</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to reset a user’s password using Active Directory Users and Computers.  Resetting a user's password using Active Directory Users and Computers (ADUC) involves changing the user's password within the Active Directory domain, allowing the user to log in with the new password. This process typically involves an administrator locating the user account, selecting the "Reset Password" option, and then providing a new password. Optionally, the administrator can also choose to force the user to change the password upon their next login. 
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Users And Computers</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Active Directory Users and Computers.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/DyoDKUD.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/ddTDbJI.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Use: Find  (OR)  Go: To the location of the user.  <a href="https://github.com/RashadHagen/ADUC-Find-Computer-User-Contact-Group-Printer-Shared-Folder-Organizational-Unit-Common-Que" style="font-family: Arial, sans-serif; font-size: 16px; font-weight: bold;">How To Find A User In Active Directory Users and Computers</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/dFAe0gH.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/38j0kTj.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The user’s name.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/lqTrAr9.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Reset Password.  Then, Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/czjjXbD.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: the password information.  NOTE: Look at the boxes below the password fields to see if you want to check any.  Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/puQ143h.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>To check the last time a password was set: Open: Command Prompt.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/y4Q3pfp.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/B9vf11H.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: net user (username) /domain.  NOTE: Because this user’s account was created using Active Directory Users and Computers and not on the local computer, you need to add /domain at the end.  Look: Towards the bottom.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/kZo2AuS.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/3CgFqnk.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
