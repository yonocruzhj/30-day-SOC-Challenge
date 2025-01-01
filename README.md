<h1>MyDFIR - 30 Day SOC Challenge (In progress)</h1>

<h2>Description</h2>

<br />


<h2>Languages and Utilities Used</h2>

- <b>Elastic and Kibana</b> 
- <b></b>

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
<h2>[Day 2: ELK Stack Introduction](https://www.youtube.com/watch?v=4AwBhXAW90Q&list=PLG6KGSNK4PuBb0OjyDIdACZnb8AoNBeq6&index=5)</h2>
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
<img src="https://imgur.com/c5tlB18.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<h2>[Day 6: Elastic Agent and Fleet Server Introduction](https://www.youtube.com/watch?v=0WklP6ZsP1g&list=PLG6KGSNK4PuBb0OjyDIdACZnb8AoNBeq6&index=10)</h2>

