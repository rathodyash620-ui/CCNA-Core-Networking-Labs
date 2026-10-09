# Lab 1: Enterprise Subnetting & Multi-VLAN Architecture

## 📌 Project Overview
This laboratory project demonstrates production-ready network design using Cisco IOS. It establishes a secure, scalable, and isolated multi-department network architecture using precise IP subnetting and modern VLAN switching principles.

## 🛠️ Network Engineering Concepts Used
* **VLSM Subnetting:** Optimized an IP block (e.g., `192.168.1.0/24`) to eliminate broadcast storm concerns and minimize IP address waste across departments.
* **Multi-VLAN Isolation:** Segregated corporate traffic by assigning different departments (HR, IT, Finance) to dedicated VLANs.
* **Inter-VLAN Routing:** Implemented a Router-on-a-Stick (ROAS) architecture using subinterfaces to handle controlled cross-VLAN communication.
* **DHCP Pools:** Automated host IP allocation per subnet via Cisco IOS DHCP servers configured directly on the core layer.

## 📂 Included Files
* `topology.pkt` / `topology.gns3` — The structural network blueprint simulation file.
* `switch_config.ios` — Clean Cisco IOS configuration script for the managed switches.
* `router_config.ios` — Clean configuration script containing the routing table rules and subinterfaces.
*
