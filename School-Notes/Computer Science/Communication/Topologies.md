One computer not connected to any other computing device is called a 'standalone'. As soon as you connect two or more computers together they form a network. A local area network such as your house is referred to as a lan.

# Bus Networks
All the nodes are connected to a single backbone cable, where each end of the backbone is connected to either a terminator or a computer which stops signals bouncing back. Each node is passive and it only sends data in one direction at a time. Only one computer can transmit successfully at any one time. CSMA with collision detection detects two nodes attempting to transmit simultaneously. Both nodes cease transmission and wait a random amount of time before reattempting. CSMA is used with wireless networks.

# Star Network
Computers are connected to a central node. This is often either a hub or a switch. A switch sends each communication to the specific computer it is intended for. A hub broadcasts the message to every computer on the LAN.

# MAC Addressing
Every network devices contains a network interface card, each NIC is attributed a unique media access control address hardcoded in manufacture. A switch holds all of the MAC addresses for each device connected to it and uses these to direct packets of data to the correct device.

The physical topology of a network defines how the devices are physically connected. THe logical topology defines how the devices communicate across the physical topologies. A network wired in star topology can behave logically as a bus network by using a bus protocol and appropriate physical switching.