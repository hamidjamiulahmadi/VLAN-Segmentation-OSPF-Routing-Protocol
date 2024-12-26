<h1>VLAN Segmentaion & OSPF Routing Protocol</h1>

<h2>Goal</h2>
This Project is about configure VLAN, Routing between VLANs, VTP, Creating SVI for the intern VLAN, HSRP for redundancy, with the use of OSPF for dynamic routing protocol and the end testing the network connectivity.in this project i will create 4 departments and connect them with each other through the OSPF routing protocol, Furthermore i will use for this lab the following devices: -> 2 Routers ( Layer 3 Devices ), 2 Multiplayer Switches ( Layer 3 Capable), 4 Access Switches ( Layer 2 ), 8 PCs and 2 Servers. 
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
then i will configure the SVI on the distribution switch.
<p align="center">
Creating SVI : <br/>
<img src="https://i.imgur.com/OZBCF7m.png" height="80%" width="80%" alt="Lab Step 5"/>
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
