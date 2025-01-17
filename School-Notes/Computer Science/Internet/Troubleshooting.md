In 1980 the International Organization Standardization publish the Open Systems Interconnection model (OSI). There are now two models (OSI or the newer TCP/IP)

# TCP/IP protocol stack
The TCP/IP uses four connected layers to allow network communication to take place. Each layer wraps the packets with its own header data:
- Application Layer
- Transport Layer
- Network Layer
- Link Layer

## Application Layer
The application layer is used to provide services for applications that want to communicate across a network, often the Internet. It uses high-level protocols that set an agreed standard between the communicating end-points. For example:
- SMTP (for e-mail)
- FTP (for file transfer)
- HTTP (for web browsing)
It does not actually determine how the data is transmitted, rather specifies the rules of what should be sent.

## Transport Layer
The transport layer uses the Transmission Control Protocol (TCP) to establish an end‐to‐end connection with the recipient computer. It splits data into packets and numbers them sequentially then adds the port number to be used based on HTTP protocol. When receiving this layer confirms that packets have been received and requests any missing packets.

## Network Layer
The network layer uses the Internet Protocol (IP) to address packets with the source and destination IP addresses. A router forwards each packet towards an endpoint called a socket, defined by the combination of IP address and port number. Each router uses a routing table to instruct the next hop.

## Link Layer
The link layer operates across a physical connection, it adds the MAC address of the physical NIC that packets should be sent to based on the destination IP address. MAC addresses change with each hop.

## Receiving Data
At the destination, the message is passed back up through the layers, the Link Layer removes the MAC address from each packet and passes it to the Network Layer. The Network Layer removes the IP address from each packet and passes it to the Transport Layer. The Transport Layer removes the port number from each packet, reassembles the packets in the correct order and passes them to the Application Layer. The Application Layer then presents the image data for the user in a browser.

## Media Access Control (MAC)
A MAC address uniquely identifies a physical device with a Network Interface Card (NIC). This may be the destination computer, or a router in transit. Packets move up and down the lower layers of the stack as they hop across routers, changing their source and destination MAC addresses as they go.

## Port numbers
A port is used to alert a specific application to deal with data sent to a computer. These are used by protocols to specify what data is being sent.

## Transferring files with FTP
File Transfer Protocol is an application level protocol used to move files across a network. FTP uses the client server model with separate data and control channels operating on ports 20 and 21. Usernames and passwords are frequently used to protect access to files and to identify users. Access can also be provided anonymously where any user can access the FTP site.