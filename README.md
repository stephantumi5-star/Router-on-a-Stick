# Router-on-a-Stick
This repository contains a Cisco Packet Tracer simulation demonstrating a complete Inter-VLAN Routing setup using the Router-on-a-Stick architecture. The topology connects multiple switches and isolated hosts across different VLANs through a single router subinterface trunk link.


# Network Topology Overview

Router (Router1): Handles inter-VLAN routing using 802.1Q subinterfaces.
Core/Access Switch (S1): Connects to the router via an 802.1Q trunk link, links to switch S2 via access port, and hosts PC0 on VLAN 10.
Access Switch (S2): Connected via a trunk link to S1 and hosts PC1 on VLAN 20.
Host Devices:
             PC0: Configured on VLAN 10 (192.168.10.0/24 subnet) with an IP address of (192.168.10.6) .
             PC1: Configured on VLAN 20 (192.168.20.0/24 subnet) with an IP address of (192.168.20.6) .
