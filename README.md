🛠️ Scalable & Fault-Tolerant Enterprise Network Design

This project demonstrates a highly scalable, redundant, and secure network architecture suitable for medium to large enterprise environments. It combines Layer 2 and Layer 3 technologies to ensure high availability, load balancing, and optimized connectivity for both wired and wireless users.

🌐 Network Overview

The network is designed to support:
Multiple VLANs for segmentation & Redundant gateways for fault tolerance & Dynamic routing QoS for IP telephony & Wireless access for mobile users & Scalable IP management and name resolution

🔧 Key Features
1. VLANs & Inter-VLAN Routing

Configured 10+ VLANs for user, server, voice, management, and guest segments

Router-on-a-Stick and SVIs (Switch Virtual Interfaces) used for inter-VLAN communication

2. Voice VLAN & QoS

Voice VLANs configured with Quality of Service (QoS) to prioritize VoIP traffic

Ensures low latency and jitter for IP phones

3. Spanning Tree Protocol

Rapid PVST+ implemented for loop prevention and fast convergence in Layer 2 domain

4. Port Security

Enabled port-level security with:

Sticky MAC addresses

MAC address limiting

Restricted violation mode for enhanced protection against unauthorized access

5. Dynamic Routing

Configured OSPF across routers for efficient, dynamic Layer 3 routing

Seamless integration between routing and switching components

6. Gateway Redundancy

Implemented HSRP (Hot Standby Router Protocol) to provide virtual default gateways

Ensures automatic failover between redundant routers

7. Wireless Infrastructure

WLC (Wireless LAN Controller) and Lightweight Access Points (CAPWAP) deployed

Wireless access provisioned for:

Employees (secure SSID)

Guests (isolated SSID)

Supports smartphones, laptops, and other wireless devices

8. Internal DNS

Internal DNS Server: 192.168.250.50 used for domain name resolution within the network

9. DHCP Services

Edge Routers act as DHCP servers

Large address pools configured to support scalable user growth

10. VoIP Support

IP Phones auto-register and receive extensions via DHCP and TFTP

Seamless peer-to-peer calling across the voice VLAN

11. Internet Access via NAT

Configured PAT (Port Address Translation) for secure internet access

Preserves internal IPs while enabling outbound connectivity

12. EtherChannel (Link Aggregation)

Core switches configured with EtherChannel for:

Link redundancy

Load balancing

Increased bandwidth between switches


🧠 Technologies Used
Cisco IOS

OSPF

HSRP

VLANs & SVIs

Rapid PVST+

DHCP, DNS

NAT (PAT)

QoS

EtherChannel

Wireless LAN Controller (WLC)

📌 Future Enhancements

Integration with SNMP for monitoring Centralized Syslog & NetFlow servers 
Firewall & VPN for secure remote access

📞 Contact
Feel free to reach out if you're interested in discussing enterprise network design, optimization, or collaboration!
🔗 LinkedIn:  https://www.linkedin.com/in/mohamedhassanhassan/
📧 Email: mohamedelshenawy34481@gmail.com
