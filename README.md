# Rocky's Pet Supply – Inter-VLAN Routing Lab

## Overview

This project simulates a small business network for **Rocky's Pet Supply** using **Cisco Packet Tracer**. The network separates departments into VLANs and uses Router-on-a-Stick inter-VLAN routing to allow communication between departments.

## Business Scenario

Rocky's Pet Supply required separate VLANs for Management, Sales, and Warehouse while maintaining communication between departments. This project demonstrates VLAN segmentation, 802.1Q trunking, and Router-on-a-Stick inter-VLAN routing.

## Network Overview

| Device | Role |
|---|---|
| RPS-RTR01 | Router |
| RPS-SW01 | Switch |
| RPS-SW02 | Switch |
| SALES-PC01 | Sales workstation |
| WHSE-PC01 | Warehouse workstation |

## VLANs

| VLAN | Name |
|---|---|
| 10 | Management |
| 20 | Sales |
| 30 | Warehouse |
| 999 | Parking_Lot |
| 1000 | Native |

## Technologies & Skills

- Cisco Packet Tracer
- Cisco IOS CLI
- VLAN configuration
- 802.1Q trunking
- Router-on-a-Stick
- Inter-VLAN routing
- IPv4 addressing
- Network troubleshooting
- Connectivity testing
- Technical documentation

## Screenshots

### Network Topology

<img width="1279" height="1005" alt="Inter-VLAN Routing Lab - Topology" src="https://github.com/user-attachments/assets/c963e73d-5e06-4ae0-8cd3-2cbdc8a1fa22" />

### VLAN Configuration

<img width="1276" height="1003" alt="Inter-VLAN Routing Lab - VLANs" src="https://github.com/user-attachments/assets/eea72005-d627-41b8-b144-5850d1c3a418" />

### Trunk Configuration

<img width="1277" height="1003" alt="Inter-VLAN Routing Lab - Trunk Configuration" src="https://github.com/user-attachments/assets/c0519934-4524-4674-b0e4-025481775322" />

### Router Interfaces

<img width="1276" height="1002" alt="Inter-VLAN Routing Lab - Router Subinterfaces" src="https://github.com/user-attachments/assets/c722ead3-e4a1-440d-b55c-ae3469d8fbc7" />

### Successful Ping Test

<img width="1278" height="1002" alt="Inter-VLAN Routing Lab - Successful Connectivity" src="https://github.com/user-attachments/assets/83c9fcb0-984d-4d85-9880-1e4d77691fa2" />

### Traceroute Verification

<img width="1278" height="1004" alt="Screenshot 2026-07-02 162015" src="https://github.com/user-attachments/assets/e015e085-c46f-4bee-aed6-7a20166104fa" />

## Key Takeaways

This project strengthened my understanding of network segmentation, VLAN trunking, router subinterfaces, and inter-VLAN routing. It also helped reinforce Cisco IOS configuration, troubleshooting, verification commands, and clear technical documentation.

## About This Project

This project is part of my IT Support and Cyber Defense portfolio and connects with my other Rocky's Pet Supply home lab projects, including Windows Server, Active Directory, and Help Desk support documentation.
