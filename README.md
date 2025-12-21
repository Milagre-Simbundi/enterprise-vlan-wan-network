Network Report

<img width="1458" height="647" alt="image" src="https://github.com/user-attachments/assets/4ff7aebd-c9a5-4d1c-bc36-347eec6ccc0f" />

This repository showcases a segmented network design connecting Library and Multimedia Facilities across two cities:

City 1: Main site

City 2: Branch site

Network Design Highlights

VLAN-Based Architecture:

Access switches (Cisco 2960) deployed in each area

Uplinked to multilayer switches (Cisco 3650) for inter-VLAN routing

WAN Connectivity:

WAN link (10.10.10.0/30) connecting core routers of both cities

Dynamic routing via RIPv2 for internal networks

Static routes for external network access

DHCP Services:

Configured on the core router

Assigns IP addresses per VLAN

Security Measures:

Unused ports shut down

VLAN trunking implemented on uplinks

End Devices:

PCs, CCTV cameras, scanners, projectors, and copiers

Devices represented physically as PCs/Printers in the diagram but correctly labelled

Communication

All end devices receive IP addresses dynamically

Successful site-to-site communication demonstrated
