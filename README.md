<h1>Active Directory Lab</h1>


<h2>Description</h2>
In this lab, I learned how to set up Active Directory on my home computer using Oracle Virtual Box.  I went through the process of installing both a Windows 10 client VM and a Server 2019 domain controller VM.  I then installed Active Directory domain services and created a dedicated domain, organizational unit, and administrator account.  Next, I installed and configured the network settings of both VMs to mimic an office environment and ran a PowerShell script to create approximately a thousand users.  At this point, I was able to successfully log on to the Windows 10 client through the domain using the usernames and passwords I added to the server. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Server 2019</b> 

<h2>Program walk-through:</h2>

<p align="center">
Oracle VM VirtualBox: <br/>
<img src="https://i.imgur.com/XCz0aYr.jpg"/>
<br />
<br />
Install Server Roles:  <br/>
<img src="https://i.imgur.com/epN8Wl0.jpg"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
