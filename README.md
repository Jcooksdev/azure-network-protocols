<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create some sample file shares with various permissions 
- Attempting to access file shares as a normal user 
- Create an Accountants security group, assigning permissions and test access 
  

<h2>Actions and Observations</h2>

<p>

</p>
<p>
1. We'll start this project by signing into our domain admin account and our Client- 1 Virtual machines. Creating 4 different folders and set permisson for each, skipping one for now. 
</p>
<br />

<p>

</p>
<p>
2. In our Client-1 we will navigate the share folder and run DC-1, seeing which folder we can access and one we are restricted from. 
</p>
<br />

<p>

</p>
<p>
3. Lastley, we will create a security group called Accountants and assign permisson and test its access. Logging out of client-1 and into DC-1, we'll assign some user to the accountant's security group and log back in as one of the users. Signing in as one user and testing which access we had assign to it earlier. 
</p>
<br />
