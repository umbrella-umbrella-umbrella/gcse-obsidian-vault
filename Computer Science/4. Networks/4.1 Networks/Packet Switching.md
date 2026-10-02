# Packet Switching
- A packet is made up of two main components: the header (and sometimes footer) and the data.

- The header contains information about the packet. This includes:
	- Addresses – sender and destination
	- Sequence number
	- Checksum
	- Type of packet
	- Time to live

- IP (internet protocol) addresses are used to identify devices in a network, including the internet.

- When you access a webpage, packets are sent to your computer using its IP  address as the destination address.

**The process, in a nutshell**
1. You click the download button on an image on a website.
2. The server containing the image receives that request via the internet.
3. The image is broken up into smaller parts.
4. Each part is put into a packet with the correct information added, including your IP address.
5. The packets make their way across the internet to your IP address. They may all take different paths and arrive in the wrong order.
6. Your computer reassembles the packets into the image. If any are missing, your computer requests they are resent.

### Routers and Traffic
- *Routers act are the traffic wardens of the network.*

- The router’s purpose is to send packets on to the next part of the network.

- Routers send each packet along a connection to another router. It usually chooses the path which has the least traffic already present. This means that packets may take different routes to their destination.

- This is called packet switching.

### Hierarchy of the Internet
- Routers
	- Direct network packets by one step in their journey from the source to the destination, i.e. to the next router in the path.
- Backbone 
	- The long distance, high bandwidth cables that travel around the region, country, or the world.
- Network Access Points (NAPs)
	- Specialised high-performance routers that handle high-speed network traffic between countries.

