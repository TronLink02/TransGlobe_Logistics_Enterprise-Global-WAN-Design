# Enterprise Global WAN Architecture Design

## 🌐 Overview
This project presents a robust network architecture designed for **TransGlobe Logistics**, a multi-regional enterprise. The solution addresses complex requirements including high-latency satellite links, global scalability, and multi-layered security.

## 🛠️ Technical Highlights
* **Subnetting:** Optimized IPv4 allocation using **VLSM** for 8 distinct VLANs, supporting over 500 hosts while preserving space for route summarization.
* **Routing:** A hybrid strategy utilizing **EIGRP** (Internal/Regional) and **OSPF** (Global Backbone) with mutual redistribution for optimal convergence and stability.
* **Infrastructure:** Three-tier hierarchical LAN design (Core/Distribution/Access) with Inter-VLAN routing via Layer 3 SVIs.
* **Quality of Service (QoS):** DSCP-based traffic classification to ensure performance for real-time applications over constrained WAN links.
* **Security:** Implementation of WPA3-Enterprise, 802.1X authentication, and host-based EDR/Application Whitelisting.

## 📊 Documentation & Proof of Concept
The repository includes a detailed technical report and Cisco Packet Tracer simulations validating:
1.  **Full End-to-End Connectivity:** Traceroute verification across global sites.
2.  **Redundancy & Failover:** Automatic OSPF path recalculation during backbone link failures.
3.  **DHCP & VLAN Segmentation:** Verified isolation and dynamic addressing for all corporate zones.

## 🚀 Skills Demonstrated
`Network Design` `VLSM` `OSPF` `EIGRP` `Cisco IOS` `QoS` `Cybersecurity` `Packet Tracer`
