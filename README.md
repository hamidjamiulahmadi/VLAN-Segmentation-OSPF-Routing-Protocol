<h1>VLAN Segmentaion & OSPF Routing Protocol</h1>

<h2>Description</h2>
This Project is about configure VLAN, Routing between VLANs, Creating SVI for the intern VLAN, with the use of OSPF for dynamic routing protocol and the end testing the network connectivity.in this project i will create 4 departments and connect them with each other through the OSPF routing protocol, Furthermore i will use for this lab the following devices: -> 2 Routers ( Layer 3 Devices ), 2 Multiplayer Switches ( Layer 3 Capable), 4 Access Switches ( Layer 2 ), 8 PCs and 2 Servers. 
<br />


<h2>Environments Used </h2>

- <b>Packet Tracer</b> 
- <b>Windows 10</b>

<h2>Configuration walk-through:</h2>

<p align="center">
Network Diagram: <br/>
<img src="https://i.imgur.com/JAwLzkr.png" height="80%" width="80%" alt="Lab Step 1"/>
<br /> 
first i will configue the VTP protocol on the distribution layer switch 1 and 2 to transmit data traffic for multiple VLANs
<p align="center">
Trunk port configuration: <br/>
<img src="https://i.imgur.com/padEIOx.png" height="80%" width="80%" alt="Lab Step 2"/>
<br />
next step, i will configure the VLAN departments on the distribution switch as you saw on the diagram and because i have configured before the VTP protocol on the distribution switch and all the down swithes will get automatically the configuration from the distribution switches.
<p align="center">
VLAN 10,20,30,40 configuration: <br/>
<img src="https://i.imgur.com/SY5PF9c.png" height="80%" width="80%" alt="Lab Step 3"/>
<br />
then i will assign each PCs to thier VLANs and Departments, here we have 8 PCs and 4 departments.
<p align="center">
VLAN 10,20,30,40 configuration: <br/>
<img src="https://i.imgur.com/pjGJIuO.png" height="80%" width="80%" alt="Lab Step 4"/>
<img src="https://i.imgur.com/UxhouZJ.png" height="80%" width="80%" alt="Lab Step 4"/>
<br />
then i will configure the SVI on the distribution switch and then for the time being of lab i will set static ip add PC1 to 10.1 PC2 to 20.1 and server1 30.1 then i will check the connection bitween PCs that they can connect with each other.
<p align="center">
Creating SVI and check the connection between PCs: <br/>
<img src="https://i.imgur.com/Hqa85iH.png" height="80%" width="80%" alt="Lab Step 5"/>
<img src="https://i.imgur.com/BK9rINj.png" height="80%" width="80%" alt="Lab Step 5"/>
<br />

<br />

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
