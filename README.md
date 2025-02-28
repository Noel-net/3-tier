# 3-tier
This repo illustrates the basic configuration of a 3-tier network configuration

I configured VPN, SSH, HSRP,port-security, VLANs, intervlans, OSPF, NAT and spanning tree in this lab.

VPN
The VPN setup aimed to facilitate secure communication between two distinct branches of the same company. However, I faced challenges due to limitations in Cisco Packet tracer commands, such as the inability to disable the tunnel keepalive feature. Consequently, the tunnel interface experienced flapping.

SSH
To securely access our devices remotely, I configured SSH on the core router and the distribution switches. 

HSRP
For gateway redundancy and seamless failover, I configured HSRP. It is a Cisco proprietary redundancy protocol used to provide gateway redundancy in a network. It ensures that if the primary router (Active) fails, a backup router (Standby) takes over seamlessly without interrupting network connectivity.

VLANS
A VLAN (Virtual Local Area Network) is a way to logically segment a network into different broadcast domains within the same physical switch. VLANs improve security, efficiency, and scalability in a network. We use VLANs to separate departments when we have a large network enterprise and to reduce congestion on a LAN network

OSPF
I used OSPF as my dynamic routing protocol. It is an open standard, and it is scalable, meaning we can use it for large network enterprises.

The username to my project is noxy, and the password is mylove

NAT
I used the network address translation (overload) to keep our internal IP address private and to easily access the internet since private IP addresses are not routable over the internet. It is a process that enables one unique IP address to represent an entire group of computers.

Port-security
On the access ports, I enable port-security, a method that adds to security by shutting down interfaces in case of a violation or allowing only a specific workstation to access our network by making the PC MAC address stick to that port.


