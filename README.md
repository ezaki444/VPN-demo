<p align="center">
<img src="https://i.imgur.com/VORrI7P.jpeg" alt="vpn-logo"/>
</p>

<h1>VPN Set up and Usage </h1>
This is a demenstration for using a VPN and observing it through an Azure machine.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Sign up or log in to Microsoft Azure
- Create a VM (virtual machine) and reasoure group naming it "vpn-test"
- Use Windows 11 pro as your image with the size having at least **2 vcpus**
- Create and connect to the VM
- On your personal computer, go to  <a href="https://whatismyipaddress.com/">whatismyipaddress.com</a></h1> and take <ins>note</ins> of your IPv6 and IPv4 address, then take <ins>note</ins> of your IP information.
  

<h2>VPN on a VM demo and download</h2>

<p>
<img src="https://i.imgur.com/7sdzfm7.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the IP address for the VM im using (yours will be different depending on where you chose to set your VM) . notice how the ISP is **Microsoft Corporation** and in a Data Center, signifying that its a VM. the IP address of this VM will be different from your Personal IP address <ins>remember that.</ins> 
</p>
<br />
<p>
<p>
  
<p>
Sign up and download Proton VPN to you ***VIRTUALMACHINE***, not your personal computer
<img src="https://i.imgur.com/JVEqa0M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
After you download it fully and open it, you should reach this screen
<p>
<img src="https://i.imgur.com/GBITnwz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in and click on the **Connect** button (if it connects near your VM or somewhere boring, click change server
</p>
<br />
<p>
<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3c1dnJpbGthNGNjY2J4emRuZmpjcWswZmo2dTdmcmx2Z3czaWdkcyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qpJhjbIDZTRW7cqDtT/giphy.gif" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now your VMs IP address has change to where ever it connected (mine was canada) and when you browse, itll be in those servers.
<br />
<p>
Now check <a href="https://whatismyipaddress.com/">whatismyipaddress.com</a></h1> and review the change of your IP addresses and information. Compare with the other IP address that you took note of.
<img src="https://i.imgur.com/IEOS5Sw.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
**Hooray!!** Youve created a RDP (remote desktop protocol) tunnel to a VM then from that VM you created a VPN tunnel. Now for me, im on my personal computer at home in **Florida**, connected to a virtual machine in **Washington**, that is connected to network in **Toronto, Canada**.
now browse and explore the differnce.
</p>
<br />
<p>
<img src="https://i.imgur.com/cOhyF7u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/zBzigrp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p
</p>
<br />
