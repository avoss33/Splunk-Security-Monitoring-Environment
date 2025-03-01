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
<img src="https://github.com/avoss33/Splunk-Security-Monitoring-Environment/blob/main/images/WindowsReport1.png?raw=true" height="80%" width="80%" alt="Windows Report 1"/></p>
<br />
<br />

- <b>Report 2 (Windows Log Severity Levels):</b>
Quickly understand the severity levels and percentages of each of the Windows logs.

<p align="center">
Windows Log Severity Levels: <br/>
<img src="https://github.com/avoss33/Splunk-Security-Monitoring-Environment/blob/main/images/WindowsReport2.png?raw=true" height="80%" width="80%" alt="Windows Report 2"/></p>
<br />
<br />

- <b>Report 3 (Comparison: Sucess and Failure of Windows Activity):</b>
Shows the organization if there is a suspicious level of failed activities on their server.

<p align="center">
Comparison of Success and Failure of Windows Activity: <br/>
<img src="https://github.com/avoss33/Splunk-Security-Monitoring-Environment/blob/main/images/WindowsReport3.png?raw=true" height="80%" width="80%" alt="Windows Report 3"/></p>
<br/>

<h3>Windows Log Alerts</h3>
- <b>Alert 1 (Level of Failed Windows Activity):</b>
Baseline and threshold for the hourly level of failed Windows activity. The average events per hour was roughly 6 events. To account for outliers, the threshold was set to 7.

<p align="center">
Level of Failed Windows Activity:</b>
<img src="https://github.com/avoss33/Splunk-Security-Monitoring-Environment/blob/main/images/WindowsAlert1.png?raw=true" height="80%" width="80%" alt="Windows Alert 1"/></p>
<br />
<br />

- <b>Alert 2 (Treshold for Successful Account Logon):</b>
Baseline and threshold for the hourly count of the signature “an account was successfully logged on.” The average events per hour was roughly 14. To account for outliers, the threshold was set to 15.

<p align="center">
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
