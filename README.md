<h1>MyDFIR - 30 Day SOC Challenge (In progress)</h1>

<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b>
- <b>Elastic and Kibana</b>
- <b>Powershell</b>
- <b>RDP</b>

<h2>Environments Used </h2>

- <b>Kali Linux</b>
- <b>Mythic</b>
- <b>osTicket Server</b>
- <b>Ubuntu Server</b>
- <b>VULTR</b>
- <b>Windows 11 Pro</b>
- <b>Windows Server</b>

<h2>Program walk-through:</h2>

<h2>Day 1</h2>
Day 1: Create Topology <br/>
<img src="https://imgur.com/vhJ19mE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Day 2: ELK Stack Introduction</h2>

### [ELK Stack Video](https://youtu.be/4AwBhXAW90Q)
<h2>Day 3: Elasticsearch setup</h2>
Day 3: Create server in VULTR<br/>
<img src="https://imgur.com/b2snJe5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 3: Connect to ELK via SSH in host terminal/powershell <br/>
<img src="https://imgur.com/uLhweU0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 3: Download and install Elasticsearch <br/>
<img src="https://imgur.com/RGovfy7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/pz62USx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 3: Change network host  <br/>
<img src="https://imgur.com/VjRgVMO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/jfkqM16.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 3: Configure firewall in VULTR <br/>
<img src="https://imgur.com/xJGPXOH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 3: Start up Elasticsearch service and confirm it is active <br/>
<img src="https://imgur.com/j0fKwFl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0mlFztk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2>Day 4: Kibana setup</h2>
Day 4: Download and install Kibana<br/>
<img src="https://imgur.com/AbJKwL8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br/>
<img src="https://imgur.com/NkAAwM5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/AeFeGUa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 4: Configure Kibana (change server port and server host) <br/>
<img src="https://imgur.com/DiXlctn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 4: Finish installing Kibana and verify status<br/>
<img src="https://imgur.com/7F7HHgK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 4: Generate Elasticsearch enrollment token for Kibana <br/>
<img src="https://imgur.com/fv5AZCZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 4: Type in private IP address through port 5601 into the web broswer <br/>
<img src="https://imgur.com/ROFS66v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Day 4: Paste enrollment token and obtain verification code following the instructions <br/>
<img src="https://imgur.com/T2pbhZz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
Day 4: Generate 3 API keys and add into keystore <br/>
<img src="https://imgur.com/fn6aGcR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/laMExQI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Day 4: Restart Kibana <br/>
<img src="https://imgur.com/JbxB5g3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>Day 5: Install Windows Server 2022 on VULTR</h2>
Day 5: Install Windows Server 2022 <br/>
<img src="https://imgur.com/owPI7hY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Day 5: Enable RDP Connection<br/>
<img src="https://imgur.com/zFF0qO5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>Day 6: Elastic Agent and Fleet Server Introduction</h2>

### [Elastic Agent and Fleet Server Video](https://youtu.be/0WklP6ZsP1g)

<h2>Day 7: Elastic Agent and Fleet Server Setup</h2>
Day 7: Create Fleet Server in VULTR<br/>
<img src="https://imgur.com/mysUVz8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
SSH and log into server<br/>
<img src="https://imgur.com/G9bCGDS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Update and upgrade Fleet Server
<img src="https://imgur.com/ROHXGPd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Allow connection to Fleet server on ELK server by opening up port 9200 <br/>
<img src="https://imgur.com/8G1M3av.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create agent policy for Windows server<br/>
<img src="https://imgur.com/F6wUxtW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change URL from from 443 to 8220 in Fleet server settings<br/>
<img src="https://imgur.com/JzMhVsI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open up Powershell in Windows server and install Elastic agent<br/>
<img src="https://imgur.com/uFSe7tM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Day 8: Sysmon Introduction</h2>


### [Sysmon Intro](https://youtu.be/hpUnKjEFCoU)

<h2>Day 9: Sysmon Installation</h2>
Download Sysmon in Windows VM<br/>
<img src="https://imgur.com/OMF9mwq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Save Olaf configuration of Sysmon and move to Sysmon folder<br/>
<img src="https://imgur.com/8xxIaHi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/tahokKh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Sysmon <br/>
<img src="https://imgur.com/C3UqbVl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Day 10: Ingest Sysmon and Windows Defender Logs into Elasticsearch</h2>
Add custom windows events logs integration in Elasticsearch
<img src="https://imgur.com/X5D97bb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Find where Sysmon logs reside and use full name where operational is as channel name
<img src="https://imgur.com/eWMEGSx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/igmoEGm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Add integration to existing agent policy created prior 
<img src="https://imgur.com/6SDWDbB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Repeat the above steps to integrate Windows Defender <br/>
<img src="https://imgur.com/lYDFmbK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ObWlUwz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Day 11: Bruteforce Attack</h2>

### [Bruteforce attack](https://youtu.be/Tv57yhAOb6g)

<h2>Day 12: Ubuntu 24.02 Installation</h2>

<h3>Objectives</h3>

-  Set up SSH Server
-  View Authentication Logs

<h4>Walk through</h4>
Add custom windows events logs integration in Elasticsearch
<img src="https://imgur.com/bMI9OGk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Observe failed attempts
<img src="https://imgur.com/o9MvTQK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Day 13: Install Elastic Agent on Ubuntu</h2>

<h3>Objectives</h3>

- Install elastic agent on Linux Ubuntu Server

<h4>Walk through</h4>
Add agent to Ubuntu server
<img src="https://imgur.com/P4w8k8T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Verify Ubuntu data is ingested in Elasticsearch
<img src="https://imgur.com/PnkGxPd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Day 14-17: Create Alerts and Dashboards in Kibana</h2>

<h3>Objectives</h3>

-  Create SSH bruteforce alert and dashboard in Kibana
-  Create RDP bruteforce alert and dashboard in Kibana
-  Create an alert and dashboard based on the telemetry generated by Mythic

<h4>Walk through</h4>
Select fields that indicate factors of brute force activity
<img src="https://imgur.com/2NuajfH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Create alert rule for SSH brute force activity
<img src="https://imgur.com/RXF6Igz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create SSH Failed Authentication - Network Map and add to new dashboard
<img src="https://imgur.com/X6vySax.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Create 2 maps in your new dashboard for accepted and failed authentication attempts 
<img src="https://imgur.com/NabB6vi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select fields source.ip and user.name
<img src="https://imgur.com/fdhiCGv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Create alert rule for RDP brute force activity
<img src="https://imgur.com/tEPYFLW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Select Choropleth and selected fields in maps
<img src="https://imgur.com/dlD9E1a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/vvZmSkc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Save map as RDP Failed Activity and add to existing dashboard created prior
<img src="https://imgur.com/iO0CAyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Repeat the process, create a map for RDP Accepted Activity, and add to existing dashboard.
<img src="https://imgur.com/XRI0oXf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/UbdTrHT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create 2 table visualizations for failed and accepted SSH authentication
<img src="https://imgur.com/aFwDCzu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Create 2 table visualizations for failed and accepted RDP authentication
<img src="https://imgur.com/B6F2MeF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>Day 17: RDP Introduction </h2>

### [RDP Intro](https://youtu.be/tNhGxtKZo7c)

<h2>Day 18:Command and Control Introduction</h2>

### [Command and control intro](https://youtu.be/WnOkhGNPmyA)

<h2>Day 19: Create Attack Diagram</h2>
<img src="https://imgur.com/7kErBUT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/PSRaXny.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/gsFB2Im.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Day 20: Mythic Server Setup</h2>

<h3>Objectives</h3>

-  Set up Mythic C2 Server
-  Learn how Mythic works

<h4>Walk through</h4>
Deploy Mythic server in VULTR
<img src="https://imgur.com/61KCHWs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
SSH into the server then update and upgrade Ubuntu 
<img src="https://imgur.com/B6waPHh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/xZyvWqQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Install prerequisites dockers-compose and make for Mythic 
Use commands "apt install docker-compose" and "apt install make" to install these prerequisites.
Clone repository
<img src="https://imgur.com/PruiEg3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Run commands
<img src="https://imgur.com/tCbQgN8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/OZJWhVd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/cgoUG0j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ys1xuyM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Create another firewall in VULTR to only allow access from SSH and Windows servers
<img src="https://imgur.com/ZMICl5F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Access Mythic from web GUI
<img src="https://imgur.com/9W057Ao.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Use command "ls -la" and "cat .env" to locate password for the account
<br />

<h2>Day 21: Mythic Agent Setup</h2>

<h3>Objectives</h3>

- Perform a brute force attack
- Generate a Mythic agent
- Establish successful C2 session

<h4>Walk through</h4>
Create password text file
<img src="https://imgur.com/IElXcbG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Change password policy on local group policy editor and log in password to password in the text file
<img src="https://imgur.com/BwtuqEv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Log into Kali through VMWare. Update and upgrade repository, then unzip rockyou.txt 
<img src="https://imgur.com/GAl3li2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/IZT03w4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Add spongebob 2025 to list of passwords
<img src="https://imgur.com/Cy98qka.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/846qOLQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</br>
Install crowbar
<img src="https://imgur.com/ZMICl5F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Access Windows from Kali Linux
<img src="https://imgur.com/0a7kDlP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Install apollo agent and C2 profile
<img src="https://imgur.com/bhBvHUj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/NbxRdPW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Create payload in Mythic
<img src="https://imgur.com/N2rh7P6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Download payload link and perform wget
<img src="https://imgur.com/IxFDq71.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Rename apollo.exe file
<img src="https://imgur.com/UWSQ02Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/t7pUBZs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Use PowerShell from Kali RDP session and run command


<br />

