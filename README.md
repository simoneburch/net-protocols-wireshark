<p align="center">
<img src="https://github.com/simoneburch/net-protocols-wireshark/assets/152559137/72121abf-ee1d-4370-92ae-3a840a7f7dd3" height="60%" width="60%" alt="Wireshark Logo"/>
</p>

<h1>Observe and Filter Network Traffic between Azure Virtual Machines</h1>
Wireshark analyzes and filters network protocols. We'll use it with command-line tools and network security groups to inspect traffic during networking activities between two virtual machines.<br />

<!--<h2>Video Demonstration</h2>

- ### [YouTube: How to Use Wireshark to Filter for Various Networking Protocols](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Wireshark
- Various Command-Line Tools
- Network Protocols (SSH, DHCP, DNS, RDP)

<h2>Operating Systems Used </h2>

- Ubuntu Server
- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Step 1: Create your Azure Resources and Install Wireshark
- Step 2: Ping your Ubuntu VM from your Windows VM (ICMP traffic)
- Step 3: Observe SSH, DHCP, DNS, and RDP Traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Filter for DHCP traffic in Wireshark. From your Windows 10 VM, issue your VM a new IP address from the command line using "ipconfig /renew".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Wireshark, filter for DNS traffic. Use "nslookup" in your Windows 10 command line to see what google.com and disney.com's IP addresses are. Also, observe the DNS traffic in Wireshark.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Wireshark, filter for RDP (tcp.port == 3389) traffic. Observe how there seems to be non-stop spam for RDP and realize it's a result of our current remote connection!
</p>
<br />
<p>Wireshark is a useful tool for network troubleshooting and analysis.</p>
