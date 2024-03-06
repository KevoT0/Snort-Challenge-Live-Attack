# Snort-Challenge-Live-Attack

<h2>Description</h2>
This a hands-on project SNORT using IDS/IPS to collect logs and create rules 
<br />

<h2>Languages and Utilities Used</h2>
- <b>Ubuntu OS</b>

<h2>Environments Used </h2>
- <b>THM Virtual Machine</b>

<h2>Walk-through:</h2>

<h3><b>TASK 1: Brute-Force</b></h3>
<p align="center">
<img src="https://i.imgur.com/jk8bSnF.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>
 
Here are the steps taken to solve the problems in Task 1

- Perform a scan utilizing the Packet logger mode to

<p align="center">
<img src="https://i.imgur.com/ZhBYge3.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

After performing the packet logger mode, I analyze the packet gotten from after utilizing the power of snort. I observed TCP packets.

<p align="center">
<img src="https://i.imgur.com/D7KP1uz.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

 A suspicious IP was found targeting SSH, having discovered this an IPS rule was created to detect any SSH traffic going into the network.

<p align="center">
<img src="https://i.imgur.com/Uyq6izC.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

After setting the rule the IPS parameter was run on the host to detect and block any SSH traffic trying to brute force into the host device.

<p align="center">
<img src="https://i.imgur.com/C25S26Z.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

 
Final Answers to the TASK 1 Questions on TryHackMe

<p align="center">
<img src="https://i.imgur.com/yLX4YeG.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

<h3>TASK 2: Reverse-Shell </h3>
<p align="center">
<img src="https://i.imgur.com/0yNHRRe.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>
 
Here are the steps taken to solve the problems in Task 2

- Perform a scan utilizing the Packet logger mode to

<p align="center">
<img src="https://i.imgur.com/ZhBYge3.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

After performing the packet logger mode, I analyze the packet gotten from after utilizing the power of snort. I observed TCP packets.

<p align="center">
<img src="https://i.imgur.com/XjaAcMS.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

 A suspicious IP was found with port 4444, having discovered this an IPS rule was created to detect any TCP traffic going into the network.

<p align="center">
<img src="https://i.imgur.com/vPHvaCg.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

After setting the rule the IPS parameter was run on the host to detect and block any Reverse shell traffic trying to gain access to the host device.

<p align="center">
<img src="https://i.imgur.com/0HiDCs9.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

The final question asked for a tool associated with the specific port number number. 

<p align="center">
<img src="https://i.imgur.com/5AXd18Y.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

 
Final Answers to the TASK 2 Questions on TryHackMe

<p align="center">
<img src="https://i.imgur.com/bYhKdoN.png" height="80%" width="80%" alt="Snort Challenge Live Attack"/>

