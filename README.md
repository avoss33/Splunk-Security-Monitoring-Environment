<h1>Designing a Splunk Security Monitoring Environment</h1>


<h2>Description</h2>
Project consists of using Splunk SIEM capabilities to build a custom security monitoring environment. Using reports, alerts, and dashboards, the objective was to ensure the created environment would make a fictional organization aware of several simulated attacks. I was tasked with monorting a Windows operating system (running many of the company's back-end operations), and an apache web server (hosting the administrative webpage).
<br/>


<h2>Languages Used</h2>

- <b>SPL</b> 

<h2>Environments Used </h2>

- <b>Splunk</b>

<h2>Program walk-through:</h2>
<h3>Windows Log Reports</h3>
- <b>Report 1 (Signatures & Associated Signature ID’s):</b>
Shows the ID number associated with the specific signature for Windows activity. Duplicate values have been removed.

<p align="center">
Signatures & Associated Signature ID’s Report: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Report 1"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
