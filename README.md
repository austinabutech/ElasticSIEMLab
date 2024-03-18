<h1>Elastic SIEM</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
A lab employing Elastic SIEM for log aggregation from Linux Fedora instances hosted on Amazon Web Services. These logs are leveraged to construct dashboards facilitating the real-time monitoring of nmap scans conducted on the machines, triggering alerts upon each scan occurrence.
<br />


<h2>Languages and Utilities Used</h2>

- <b>ElasticSearch SIEM</b> 
- <b>Amazon Web Services</b>

<a href="https://www.elastic.co/">ElasticSearch </a>

- <b>AWS Fedora</b> 

<h2>Program walk-through:</h2>

<p align="center">
1.	Obtain elastic agent and add to Fedora host. Integration> elastic defence> add integration <br/>
<img src="pic1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2.	Push and install agent on Amazon linux Fedora VM using curl command below:  <br/>
<img src="Pic2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
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
