Network Report
The diagram represents a segmented network design connecting Library and Multimedia Facilities across two cities (City 1 as the main site and City 2 as the branch), with a focus on City 2.
It showcases a VLAN-based architecture where access switches (2960) are used in each area and uplinked to a multilayer switch (3650) for inter-VLAN routing.

A WAN link (10.10.10.0/30) connects the core routers of both cities, with RIPv2 enabling dynamic routing between internal networks static routes providing access to external networks. 
The design includes DHCP services configured on the core router, assigning IP addresses per VLAN, and security measures include shutting down of unused ports and implementing VLAN trunking on uplink ports. 
End devices, including PCs, cameras, scanners, and projectors, receive IP addresses dynamically and demonstrate successful site-to-site communication.
NOTE: Devices such as scanner, presentation board, CCTV cameras, network projector and copiers, are physically represented by PCs (for CCTV cameras, presentation board, network projector) and Printers (for Scanners and Copiers) in the diagram, but they are correctly labelled with their actual names.
