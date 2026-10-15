## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 	15.10.2026	

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram
<img width="1920" height="1080" alt="Screenshot 2026-10-15 172758" src="https://github.com/user-attachments/assets/9e029edd-8833-4acd-8add-95156ad6e8de" />



________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)

<img width="1920" height="1080" alt="Screenshot 2026-10-15 172437" src="https://github.com/user-attachments/assets/5a2220c2-ae6e-4625-ae75-daa219e41c34" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e3c364c7-9f32-44b2-b3d5-c03540e535c1" />
<img width="1920" height="1080" alt="Screenshot 2026-10-15 174001" src="https://github.com/user-attachments/assets/62363118-17f7-4197-990f-28703afb98e5" />

___________
_____________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
