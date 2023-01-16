<h1>Traffic Analysis Investigation</h1>

<h2>Description</h2>
This traffic analysis project was one of many projects I did for my MSCIA degree. The compromise that was investigated happened on November 21, 2015, at 9:03 AM MST. This compromise took place within the network that was compromised, it was not an external attack. The compromise started with the intruder performing scans looking for a way to get to the target computer. The compromise started on the computer with the IP address 10.0.7.54 running Linux. This was determined by looking at the time to live which was 64. This is consistent with Linux. The attack failed with the IP address 10.0.7.54. 
<br />
<br />
The intruder was successful in the attack with IP address 10.0.7.50. The computer compromised had an IP address of 10.210.210.210 running Windows server 2003. The intruder transferred files onto the computer used to extract passwords. The files used to extract passwords in the compromise were pwdump2.exe and samdump.dll. The intruder was able to extract password hashes to the file l.txt. The intruder than exported the file to 10.0.7.50. The intruder deleted the files that were used in the compromise when the attack was finished. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Wireshark</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)

<h2>Screenshots analyzing network traffic in Wireshark:</h2>

<p align="center">
<br />
Start of Atttack:  <br/>
<img src="https://user-images.githubusercontent.com/122753132/212724576-3491ea5c-354a-45f5-a339-04fd4a6b8ce7.png" height="80%" width="80%" alt="Traffic Analysis"/>
<br />
<br />
Traffic Analysis: <br/>
<img src="https://user-images.githubusercontent.com/122753132/212727742-472a4b8d-c6d6-428f-b89e-e1a643ea46ca.png" height="80%" width="80%" alt="Traffic Analysis"/>
<br />
<br />
Traffic Analysis:  <br/>
<img src="https://user-images.githubusercontent.com/122753132/212728273-728ef3d6-161c-481f-83c5-a69150054a78.png" height="80%" width="80%" alt="Traffic Analysis"/>
<br />
<br />
Traffic Analysis:  <br/>
<img src="https://user-images.githubusercontent.com/122753132/212728681-8faa8c93-30b2-493c-a155-28a776d5f15f.png" height="80%" width="80%" alt="Traffic ANalysis"/>
<br />
<br />
Traffic Analysis:  <br/>
<img src="https://user-images.githubusercontent.com/122753132/212729018-d99479c9-55b6-41c8-9356-645887d5fbca.png" height="80%" width="80%" alt="Traffic Analysis"/>
<br />
<br />
Traffic Analysis:  <br/>
<img src="https://user-images.githubusercontent.com/122753132/212729362-d2225a0c-f79e-4977-bf4b-c7a0a2ea8c59.png" height="80%" width="80%" alt="Traffic Analysis"/>
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
