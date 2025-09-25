# Router-on-a-stick

This project illustrates **Router-on-a-Stick (RoAS)** configuration with Cisco Packet Tracer.
It facilitates communication among multiple VLANs through a single router interface with sub-interfaces.

## Topology

- **1 Router (Cisco 2911)**
- **1 Switch (Cisco 2960-24TT)**
- **4 PCs** (split into two VLANs: 10 & 20)


## IP Addressing

- **VLAN 10:** 192.168.10.0/24  
- **VLAN 20:** 192.168.20.0/24  

## Features

- VLAN segmentation
- Routing between VLANs using sub-interfaces
- Assignment of gateway per VLAN

## Usage

1. Start `router-on-a-stick.pkt` in Cisco Packet Tracer.
2. Check the configuration of VLAN on the switch.
3. Configure sub-interfaces on the router.
4. Test connectivity using `ping` between PCs belonging to different VLAN
