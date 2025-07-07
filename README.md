<h1>Lab 2: Azure Compute and Networking </h1>

<h2>Description</h2>
In this lab, we're creating our first remote desktop with Windows & Linux in Azure.  We will continue with our previous subscription to achive this lab.

<h2>Languages and Utilities Used</h2>

- <b>Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (23H2)
- <b>Windows 10</b> (22H2)
- <b>Linux [Ubuntu]</b> (22.04)

<h2>Program walk-through:</h2>

<p align="center"><b>
#1. Create a Resource Group in Azure: <br/>
<br />
<img src="https://i.imgur.com/2QWGUNK.png" height="80%" width="80%"/>
<br />
<br />
#2. Create a Windows 10 VM: <br/>
<br />
<img src="https://i.imgur.com/nznZCnN.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/MxHpwsd.png" height="80%" width="80%"/>
<br />
<br />
#3. Create a Linux VM with Ubunutu: <br/>
<br />
<img src="https://i.imgur.com/CvvYi0H.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/jydYSKR.png" height="80%" width="80%"/>
<br />
<br />
#4. Use Remote Desktop to connect to your Windows 10 Virtual Machine <br />
<br />
<img src="https://i.imgur.com/MdZOptg.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/Nsi8x88.png" height="80%" width="80%"/>
<br />
<br />
#5. Once connected, Download WireShark on your Windows 10 VM: <br/>
<br />
<img src="https://i.imgur.com/mz8aggj.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/PfUjZxF.png" height="80%" width="80%"/>
<br />
<br />
#6. Open WireShark and Begin a packet capture: <br/>
<br />
<img src="https://i.imgur.com/tqUD1KY.png" height="80%" width="80%"/>
<br />
<br />
#7. Filter to IMCP traffic only: <br/>
<br />
<img src="https://i.imgur.com/94WPHFo.png" height="80%" width="80%"/>
<br />
<br />
#8. Retrieve the private IP address of the Linux VM and attempt to ping it to the Windows 10 VM: <br/>
<br />
<img src="https://i.imgur.com/kNDhnA4.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/1EB3Lio.png" height="80%" width="80%"/>
<br />
<br />
#9. Initiate a non-stop ping from your Windows 10 VM to your Linux VM: <br/>
<br />
<img src="https://i.imgur.com/4WTVeT1.png" height="80%" width="80%"/>
<br />
<br />
#10. Once the ping is initiate, Go to Azure and disable incoming pings <br/>
<br />
<img src="https://i.imgur.com/97VQLvo.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/EGopEMR.png" height="80%" width="80%"/>
<br />
<br />
#11. Observe the disabled traffic <br/>
<br />
<img src="https://i.imgur.com/NBGs2Kn.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/OZjOAqI.png" height="80%" width="80%"/>
<br />
<br />
#12. Once observe, Delete the disable command <br/>
<br />
<img src="https://i.imgur.com/yig2Tl4.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/D7N2jF4.png" height="80%" width="80%"/>
<br />
<br />
</p></b>
