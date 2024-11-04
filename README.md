# Networking
Networking is the process of making connections and building relationships. These connections can provide you with advice and contacts, which can help you make informed career decisions. Networking can even help you ﬁnd unadvertised jobs/internships. 
## Bridge
A Linux bridge behaves like a network switch. It forwards packets between interfaces that are connected to it. It's usually used for forwarding packets on routers, on gateways, or between VMs and network namespaces on a host. It also supports STP, VLAN filter, and multicast snooping.![image](https://github.com/user-attachments/assets/68cc735f-9b76-4a91-b55a-495c74b0a1b3)
## VLAN
A VLAN, aka virtual LAN, separates broadcast domains by adding tags to network packets. VLANs allow network administrators to group hosts under the same switch or between different switches.![image](https://github.com/user-attachments/assets/729a0c03-e2ee-43c7-97dd-94ad03b4d500)
## VXCAN
Similar to the VETH driver, a VXCAN (Virtual CAN tunnel) implements a local CAN traffic tunnel between two VCAN network devices. When you create a VXCAN instance, two VXCAN devices are created as a pair. When one end receives the packet, the packet appears on the device's pair and vice versa. VXCAN can be used for cross-namespace communication.![image](https://github.com/user-attachments/assets/def54c72-f54b-454f-8f1a-9c58922c0fe3)
## MACVLAN
With VLAN, you can create multiple interfaces on top of a single one and filter packages based on a VLAN tag. With MACVLAN, you can create multiple interfaces with different Layer 2 (that is, Ethernet MAC) addresses on top of a single one.![image](https://github.com/user-attachments/assets/58172f4c-72dc-4e35-98b3-32e78000c938)
## IPVLAN
IPVLAN is similar to MACVLAN with the difference being that the endpoints have the same MAC address.![image](https://github.com/user-attachments/assets/94499918-a43b-4d74-9164-c1f623e7e8f8)
## VETH
The VETH (virtual Ethernet) device is a local Ethernet tunnel. Devices are created in pairs, as shown in the diagram below.![image](https://github.com/user-attachments/assets/d271d51d-a33a-4c9b-bf8b-34c5342db046)
## VCAN
Similar to the network loopback devices, the VCAN (virtual CAN) driver offers a virtual local CAN (Controller Area Network) interface, so users can send/receive CAN messages via a VCAN interface. CAN is mostly used in the automotive field nowadays.
## VXCAN
Similar to the VETH driver, a VXCAN (Virtual CAN tunnel) implements a local CAN traffic tunnel between two VCAN network devices. When you create a VXCAN instance, two VXCAN devices are created as a pair. When one end receives the packet, the packet appears on the device's pair and vice versa. VXCAN can be used for cross-namespace communication.
## ovs open virtual switch
Open vSwitch (abbreviated to OVS) is a production quality, multilayer virtual switch. It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (for example, NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).![image](https://github.com/user-attachments/assets/c15ffda1-9d59-43af-98f5-1bc9b22930e6)
## Tun Tap
TUN, namely network TUNnel, simulates a network layer device and operates in layer 3 carrying IP packets. TAP, namely network TAP, simulates a link layer device and operates in layer 2 carrying Ethernet frames. TUN is used with routing. TAP can be used to create a user space network bridge.![image](https://github.com/user-attachments/assets/63b86034-18fb-4cd3-a6d1-288285946c65)
