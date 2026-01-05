# Enterprise VLAN WAN Netwok
<img width="1458" height="647" alt="image" src="https://github.com/user-attachments/assets/4ff7aebd-c9a5-4d1c-bc36-347eec6ccc0f" />

## Overview

This project demonstrates the design and implementation of a segmented enterprise network connecting Library and Multimedia facilities across two geographically separated sites using Cisco Packet Tracer.

The network is built following enterprise networking principles, including VLAN segmentation, inter-VLAN routing, WAN connectivity, dynamic routing, DHCP services, and basic security hardening.

## Network Topology Overview

City 1 – Main Site

City 2 – Branch Site

Each site supports multiple departments and shared resources, ensuring scalability, security, and efficient traffic management.

## Network Design Highlights
## VLAN-Based Architecture

Multiple VLANs created to logically separate departments and services

Cisco 2960 access switches deployed for end-device connectivity

Cisco 3650 multilayer switches used for inter-VLAN routing

## WAN Connectivity

Point-to-point WAN link: 10.10.10.0/30

Connects core routers between City 1 and City 2

RIPv2 configured for internal dynamic routing

Static routes implemented for external network access

## DHCP Services

Centralized DHCP service configured on the core router

Automatic IP address assignment per VLAN

Simplifies host configuration and improves manageability

## Security Measures

All unused switch ports administratively shut down

VLAN trunking configured only on authorized uplink ports

Network segmentation reduces broadcast traffic and improves security

## End Devices

PCs

CCTV Cameras

Scanners

Projectors

Copiers

Devices are represented physically as PCs or printers in Packet Tracer but are logically labelled according to their real-world function.

## Network Communication

All end devices successfully obtain IP addresses via DHCP

Full site-to-site communication verified across the WAN

Inter-VLAN and inter-site routing functioning correctly

## Testing & Validation

Verified DHCP address allocation per VLAN

Confirmed inter-VLAN routing on multilayer switches

Tested WAN connectivity between sites

Successful end-to-end communication confirmed using ICMP (ping)

## Technologies Used

Cisco Packet Tracer

VLANs & Trunking (802.1Q)

Inter-VLAN Routing

RIPv2

Static Routing

DHCP

Basic Switch Security
