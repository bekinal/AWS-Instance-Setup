<h1>AWS Instance Setup</h1>

<h2>Description</h2>
Project consists of creating an EC2 instance of Windows Server 2016 with basic configuration. Then, the instance is connected to via RDP. 
<br />


<h2>Utilities Used</h2>

- <b>Amazon Web Services</b>

<h2>Environments Used </h2>

- <b>Windows 2016 Server</b>

<h2>Creating a new EC2 instance:</h2>
The EC2 dashboard is navigated to. "Launch Instance is selected":<br/>
<img src="https://imagizer.imageshack.com/img922/2226/kOpvnp.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Under "Choose an Amazon Machine Image (AMI)", Windows 2016 is searched. The first option is selected:<br/>
<img src="https://imagizer.imageshack.com/img923/1862/PorDiA.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A new key pair is created. This is saved in order to access the password for RDP:<br/>
<img src="https://imagizer.imageshack.com/img924/778/rBUd6r.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A new basic security group will be created upon starting the instance. RDP traffic is allowed from the users IP only:<br/>
<img src="https://imagizer.imageshack.com/img923/3179/cM5vhD.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch Instance is selected, and View all instances is clicked to navigate back to the EC2 dashboard:<br/>
<img src="https://imagizer.imageshack.com/img923/5285/H8YQC5.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Connecting to the instance via RDP:</h2>
Under the EC2 dashbord, the new instance is right-clicked. "Connect" is selected:<br/>
<img src="https://imagizer.imageshack.com/img924/7017/D9vo92.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The password is decrypted using the key pair .pem file created earlier. The password will be decrypted and saved in a text file:<br/>
<img src="https://imagizer.imageshack.com/img922/3522/aIraZA.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The Remote Desktop Connection window is viewed. Connect is selected:<br/>
<img src="https://imagizer.imageshack.com/img924/5992/Vr7qE2.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The password decrypted from eariler is entered. After some configuration, the instance is now functional:<br/>
<img src="https://imagizer.imageshack.com/img922/8213/HQGM1Z.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
