<h1>JWipe - HOME LAB ACTIVITIES</h1>

 ### [ANALYZE | CAPTURE PACKET DEMONSTRATION]

<h2>Description</h2>

<br> PERFOM TASKS ASSCOCIATED WITH USING TCPDUMP TO CAPTURE NETWORK TRAFFIC ON A LINUX ENVIRONMENT.</>


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>WINDOWS SQL</b>

<h2>Environments UseD </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Used IFCONFIG to identify the interface that are available: <br/>
<img src="https://imgur.com/a/HYT5iQv" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
The command returns output similar to the following:  <br/>
<img src="https://imgur.com/a/06NhGrm" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
Filter live network packet data from eth0 interface with tcpdump: <br/>
<img src="" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
This outputs a detailed look at the packet information:  <br/>
<img src="https://imgur.com/a/kZPx1PJ" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
In the example data at the start of the packet output, tcpdump reported that it was listening on the eth0 interface, and it provided information on the link type and the capture size in bytes::  <br/>
<img src="https://imgur.com/a/fS7SkGx" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
Capture packet data into file called capture.pcap:  <br/>
<img src="https://imgur.com/a/FQtz9VY" height="80%" width="80%" alt="Packet Capture Steps"/>
<br />
<br />
used curl to generate some HTTP(port 80)traffic:  <br/>
<img src="https://imgur.com/a/re6RNuY" height="80%" width="80%" alt[="]Packet Capture Steps"/>
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
