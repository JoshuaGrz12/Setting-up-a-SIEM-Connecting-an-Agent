# Setting-up-a-SIEM & Connecting-an-Agent
<h2>Languages and Utilities Used</h2>

- <b>Kali Linux</b>
- <b>Ubuntu</b>
- <b>Wazuh</b>

<h2>Environments Used </h2>

- <b>Oracle Virtual box</b> 

<h2>Project walk-through:</h2>

<p align="center">
Using wazuh code provided on Ubuntu VM to ensure this is where I want the Wazuh host server to be on: <br/>
<img src="https://i.imgur.com/N9iZ8I8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verifying what IP ad is going to be used for Wazuh Server:  <br/>
<img src="https://i.imgur.com/1xGGG6w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Seeing that Wazuh Server is up and running and now need to deploy an agent onto the server, <br/>
<br />
<br />
Now on KaliLinux VM I'm going to put in the code to make this VM into an agent, connecting it to the Wazuh sever
:  <br/>
  <img src="https://i.imgur.com/WTrZLRw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Checking on Wazuh server to ensure the agent is connected and running 
:  <br/>
  <img src="https://i.imgur.com/V4N7WX9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now I will be showing an example a privilege escalation with sudo on the KaliLinux Agent:  
:  <br/>
  <img src="https://i.imgur.com/AYeKQ1K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Looking at the Wazuh Server it shows that "Privilege EscalationDefense Evasion" tactic was used from a first time user:  
:  <br/>
  <img src="https://i.imgur.com/6VEd3BW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
