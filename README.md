<h1>SIEM for monitoring failed RDP attacks</h1>



<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>



<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<h2>Attacks coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="Incoming attacks.png" height="85%" width="85%" alt="Incoming Attacks"/>

<h2>Map of incoming attacks after 24 hours<h2>

<p align="center">
<img src="attacksmap.png" height="85%" width="85%" alt="attacks map"/>

</p>

