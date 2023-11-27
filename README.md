<h1>userCreation - Automated User Account Creation In Active Directory</h1>

 ### Article I Wrote To Demonstrate The Script -
 ### [userCreation - A PowerShell Script That Automates Bulk User Account Creation In Active Directory](https://medium.com/@dante.falls/managing-active-directory-user-accounts-with-powershell-2bd988f9d7df)

<h2>Description</h2>
userCreation.ps1 is a PowerShell script that goes through a list of names that you provide and creates a domain user account for each name in the list. The script is designed to be used in an Active Directory domain environment. 
Click on the medium article above to learn how to use the script. I will also demonstrate the script, below. 
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>

### Name List Generator -
### [Click This Link For A Website That Creates A Random List Of Names](https://www.randomlists.com/random-names)

<h2>Program walk-through:</h2>

<p align="center">
Here Is The List Of Names Our Script Will Use To Create The User Accounts: <br/>
<img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*in7d1xewF4q4Mq9PvE8oaQ.png" height="300%" width="300%" alt="userCreation Demonstration"/>
<br />
<br />
Run The userCreation.ps1 Script From The PowerShell Command Line:  <br/>
<img src="https://miro.medium.com/v2/resize:fit:3560/format:webp/1*CX5d38l-nn7OOlNuBmnW7Q.png" height="300%" width="300%" alt="userCreation Demonstration"/>
<br />
<br />
Check Active Directory Users And Computers To Verify That Your Script Created The User Accounts:  <br/>
<img src="https://miro.medium.com/v2/resize:fit:3824/format:webp/1*9QvoeSUCeZp1z_fgbIW_0w.png" height="300%" width="300%" alt="userCreation Demonstration"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
