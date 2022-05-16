<h1>Coinbase Price Predictor</h1>

<h2>Description</h2>

The Powershell script in this repository is used to parse out Windows Event Log information for failed RDP attacks and uses a third party API (ipgeolocation.io) to collect geographic information about the attackers location.

To begin this analysis, Azure Sentinal must be set up. We will use Sentinal as a SIEM (Security Information and Event Management) to detect failed RDP Brute Force attacks. These attacks will take place on a live virtual machine connected to our SIEM to be used as a honey pot. These attempts will be observed and analyzed from around the world with the help of a custom PowerShell script to plot the attacker's Geolocation info and plot it on an Azure Sentinal Map. 
<br>

<h2>Tools and Utilities Used</h2>
- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer to Microsoft Azure.
<br />

<h2>Version History</h2>
- <b>[v0.1.0]:</b>

<h2>Milestones to reach</h2>
- <b></b>

<h2>Current Tasks</h2>
- <b></b>
