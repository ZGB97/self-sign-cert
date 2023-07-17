<h1>Public Key Infrastructure </h1>


<h2>Description</h2>
 Creating a Self-signed Certificate in Linux
<br />


<h2>Languages and Utilities Used</h2>

- <b>Kali Linux </b> 

<h2>Screenshots:</h2>

<p align="center">
Install Open SSL: <br/>
<img src="https://i.imgur.com/nNgEzkP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create directory for storing the private key and ensuring the directory is not readable by anyone except the root user:  <br/>
<img src="https://i.imgur.com/B5Xy2bP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate key with the Open SSL command: <br/>
<img src="https://i.imgur.com/U9YOgvl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Remove passphrase from the private key: <br/>
<img src="https://i.imgur.com/AmRtTmn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate Certificate Signing Request (CSR): <br/>
<img src="https://i.imgur.com/hLdWBen.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Completed CSR:  <br/>
<img src="https://i.imgur.com/sYDAsDo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generate certificate file from CSR and the Private key files:  <br/>
<img src="https://i.imgur.com/ANbmgr6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ensure files are not accessible to other users:  <br/>
<img src="https://i.imgur.com/RX3a3JN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Self-signed Certificate:  <br/>
<img src="https://i.imgur.com/ZQiqOiR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
