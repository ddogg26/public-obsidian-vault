
1. **Physical Layer (Bits)**
	* Handles transmission of raw data
	* Hardware elements like cables, repeaters, hubs (repeaters and hubs because they transmit data, no data processing)
	* Fiber optics and Wi-Fi operate at this layer

2. **Data Link Layer (Frames)**
	* Ensures reliable data transfer between nodes
	* Node-to node data transfer, error detection and correction
	* Manages MAC addresses
	* Ethernet, PPP (Point-to-Point Protocol)

3. **Network (Packet)**
	* Data routing, forwarding, and addressing
	* Determines the best physical path for data based on network conditions, priority of service, etc
	* IP addresses, packet forwarding
	* IP, ICMP (Internet Control Message Protocol), RIP (Routing Information Protocol)

4. **Transport (Segment/Datagram)**
	* Reliable end-to-end communication between hosts
	* Segments and reassembles data for transmission, more error detection
	* TCP and UDP
	* TCP reliable with error checking and three way handshake (SYN, SYN/ACK, ACK), good for email, file transfer
	* UDP doesn't establish connection first, faster, good for stuff like video streaming

5. **Session (Data)**
	* Controls the connections between computers (establish, termination)
	* RPC (Remote Procedure Call)

6. **Presentation (Data)**
	* Translates data between application layer and network format
	* Handles data formatting, encryption, compression
	* ASCII, UTF-8, etc
	* AES, RSA

7. **Application (Data)**
	* Allows applications to access network services
	* Interface between end-user and network services
	* Resource sharing, remote file access, network management
	* HTTP, FTP, SMTP, DNS, etc

#### Full Story Example
 