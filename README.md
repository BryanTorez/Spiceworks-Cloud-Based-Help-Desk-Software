<h1>Spiceworks - Cloud Based Help Desk Software</h1>


<h2>Description</h2>
So far, throughout the past projects, I've learned the policies and procedures for providing good customer service. Yet, my single area of weakness in learning the help desk is a typical Remote Desktop Protocol (RDP) program tool. Spiceworks, a Cloud Based Help Desk Software, has a remote desktop tool feature that allows a user to connect to a computer in another location, see the computer's desktop and interact with it as if it were local troubleshoot.


<br />


<h2>Utilities used...</h2>

- <b>Docker</b> 
- <b>Linode</b>
- <b>Linux Virtual Machine</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>
- <b>Linux (Ubuntu 24.10)</b>

<h2>Platform walk-through:</h2>

<p align="center">
Go to https://www.virtualbox.org/wiki/Download_Old_Builds_7_0 and download the latest build: <br/>
<br />
<img src="https://snipboard.io/JeV6UE.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/OZWA4n.jpg" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Go to https://ubuntu.com/download/desktop and download the latest build : <br/>
<br />
<img src="https://snipboard.io/BQOE8N.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Go to https://ubuntu.com/download/desktop and download the latest build : <br/>
<br />
<img src="https://snipboard.io/VRxr9e.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Go to your settings on your Windows operating system: <br/>
<br />
<img src="https://snipboard.io/StLp6g.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Go to System > Recovery and press "Restart Now" right next to Advanced startup and wait:  <br/>
<br />
<img src="https://snipboard.io/qJF3sA.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Click the troubleshoot option:  <br/>
<br />
<img src="https://snipboard.io/cpQ6fZ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Click the UEFI Firmware Settings optiion:  <br/>
<br />
<img src="https://snipboard.io/QZYOHp.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Once in your BIOS, enable virtualization under advanced settings:  <br/>
<br />
<img src="https://snipboard.io/kSRVIm.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Press the Esc key to exit without saving any changes. Press the F10 or F12 key to save changes and exit.:  <br/>
<br />
<img src="https://snipboard.io/CVeczi.jpg" height="10%" width="100%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Once out of your BIOS, boot up Virtual Box and click on the New option:  <br/>
<br />
<img src="https://snipboard.io/2SvGYg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Once on this page, enter the installation file of linux into the ISO Image option. Next, name the virtual machine "Linux" and create:  <br/>
<br />
<img src="https://snipboard.io/h8RdBW.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Enable the Guest Additions option and press next:  <br/>
<br />
<img src="https://snipboard.io/n2cLgt.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Choose the amount of memory and processing power you'd like to give to the virtual machine. (A good amount is the base line for where I put my two markers, we're gonna be using this virtual machine for a short minute so it doesn't matter how low you go but just make sure to not put your own markers so high. We don't wanna break your system... -_-:  <br/>
<br />
<img src="https://snipboard.io/9eNxyt.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
For the rest of the configuration pop-ups, click next for the default option. Choose a low amount of storage; it's not necessary. Finally, click Create.:  <br/>
<br />
<img src="https://snipboard.io/bj6WMv.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Once created, press Start on Virtual Lab. Then click on Try on Install Ubuntu, then wait:  <br/>
<br />
<img src="https://snipboard.io/fI8i1x.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Enter the configurations that you'd like:  <br/>
<br />
<img src="https://snipboard.io/7YCvAq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/UvObIq.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/jwxlyn.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Click on the Erase Disk and Install Ubuntu option and press on Install Now:  <br/>
<br />
<img src="https://snipboard.io/po7a8m.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Create your account:  <br/>
<br />
<img src="https://snipboard.io/06xSni.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Wait for the download and then click Restart Now when done:  <br/>
<br />
<img src="https://snipboard.io/tpyk3o.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Enter your account information:  <br/>
<br />
<img src="https://snipboard.io/VcLZmE.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Once on the home of your operating system, click on Terminal:  <br/>
<br />
<img src="https://snipboard.io/N8vCqU.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/T16S5R.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
Follow the commands on the terminal:  <br/>
<br />
<br />
<br />
These commands ensure that both docker and docker composed are installed. If it's not, then it'll download for you:  <br/>
<br />
<img src="https://snipboard.io/GC68jJ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/wljNFT.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/OrkgF3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/vc15Ji.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
When you're at this page you're gonna need to copy and paste the command from https://github.com/Peppermint-Lab/peppermint back to the original page. When done copying and pasting you're gonna wanna press ctrl+x, ctrl+y, ctrl+enter to save:  <br/>
<br />
<img src="https://snipboard.io/3pdxym.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://snipboard.io/utfID9.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://snipboard.io/tVC5PT.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
This command starts your Docker application and all services in the YAML file. When you enter this command, wait for the command to download:  <br/>
<br />
<img src="https://snipboard.io/dQZtro.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
The page should read the IP address including the host that you need to enter into your web search bar engine. By entering the IP address, host, and website link you will be sent to your own homemade peppermint ticketing system login:  <br/>
<br />
<img src="https://snipboard.io/7Vr9zd.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/bXlZDU.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://snipboard.io/V38Weo.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
The password and your email address is the same for every individual since the link to the website is already specified alone to every user. The email address is admin@admin.com. The password is 1234.:  <br/>
<br />
<img src="https://snipboard.io/Yqklg7.jpg" height="100%" width="100%" alt="Disk Sanitization Steps"/>` 

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
