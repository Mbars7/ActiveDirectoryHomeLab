<h1>Active Directory Home Lab</h1>


<h2>Description</h2>
In this lab, I learned how to set up Active Directory on my home computer using Oracle Virtual Box.  I went through the process of installing both a Windows 10 client VM and a Server 2019 domain controller VM.  I then installed Active Directory domain services and created a dedicated domain, organizational unit, and administrator account.  Next, I installed and configured the network settings of both VMs to mimic an office environment and ran a PowerShell script to create approximately a thousand users.  At this point, I was able to successfully log on to the Windows 10 client through the domain using the usernames and passwords I added to the server. 
<br /><br>


- Active Directory Administration: using PowerShell to automate provisioning and maintenance of users accounts<BR>
- Setting up Remote Access Server (RAS) features to support NAT/PAT<br>
- Implementation and maintenance of Windows DNS and DHCP services<br>
- Configuration of Windows File Servers with implementation quotas and NTFS permissions<b></b>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Server 2019</b> 

<h2>Project Snapshots:</h2>

<p align="center">
Oracle VM VirtualBox: <br/>
<img src="https://i.imgur.com/AL0Ssgs.jpg"/>
<br />
<br />
Installed Server Roles:  <br/>
<img src="https://i.imgur.com/C7cVUsC.jpg"/>
<br />
<br />
IP Settings: <br/>
<img src="https://i.imgur.com/zcGL1Q5.jpg"/>
<br />
<br />
DHCP Setup:  <br/>
<img src="https://i.imgur.com/rVYLS25.jpg"/>
<br />
<br />
Active Directory Users:  <br/>
<img src="https://i.imgur.com/xIVkb0N.jpg"/>
<br />
<br />
Active Directory Computers:  <br/>
<img src="https://i.imgur.com/zEnop5P.jpg"/>
<br />
<br />
Client Login:  <br/>
<img src="https://i.imgur.com/jQGki5m.jpg"/>
</p>

Credit for Home Lab: [Josh Madakor](https://www.youtube.com/watch?v=MHsI8hJmggI&ab_channel=JoshMadakor)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
