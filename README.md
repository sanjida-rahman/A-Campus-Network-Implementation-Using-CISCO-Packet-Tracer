# A-Campus-Network-Implementation-Using-CISCO-Packet-Tracer

In this project, using CISCO packet tracer, a campus network consisting two departments (CSE and ECE) and an admin office is designed.

**Network for Department of ECE:**

• A PT-Router is connected to a switch with Fast Ethernet 0/0 with a 2960 switch, the IP address used for this network is 190.168.10.0 and the IP address for the router is 190.168.10.1.

• The router is also connected to the admin office router in serial 2/0 where the network address is 20.10.10.0 and the IP address set in this router is 20.10.10.1.

• For both of the router and switch, enable secret password was set. For the router telnet password is also set. 

• Password was set in the connected PC in Static manner.

• VLAN 10 is assigned to the students (PC0,PC1 and PC3) and VLAN 20 is assigned to the faculty (PC3 and PC12). Trunk ports are configured to allow VLAN traffic. Access ports are assigned to specific VLANs

**Network for the Admin Office:**

• A PT-router is used for the admin office which is connected to three networks. The networks are Fast Ethernet0/0, Serial 2/0 and Se3/0, the network addresses are 190.168.20.0, 20.20.20.0/ and 20.20.20.0 respectively.

• Both the router and switch are enable password protected.

• A DNS server is added to the network to resolve domain names to IP addresses.

• A web server is also added to this admin office network. It was configured with a static IP address for consistent access. In the index.html file, the title is changed to ‘Open ended Lab’ which is shown while web browsing through every hosts.

