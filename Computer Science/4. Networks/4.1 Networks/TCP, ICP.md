
- Protocols are the sets of rules that computing devices follow in order to communicate
- A layered protocol stack is a set of protocols  that interact with one another, but are not  concerned with how each other work.

 ![[tcpimage.png]]

### TCP/TP Stack
- TCP/IP is a layered protocol stack that enables communication on the internet.
- Each layer in the stack is responsible for a particular part of the process.
- Each layer produces a result which is used by the next, being passed lower or higher.
- Layers cannot be skipped.
- Both the sending device and receiving device use all layers of the stack.

- (Through the layers)
	- Finally the Link layer (or Network Interface layer) is responsible for transporting the raw data over the transmission medium. This includes generating the right type of signal for the connection type – light for fibre, electrical for ethernet, etc.
	- The receiving computer follows the  same process but in reverse.
	- The signal is translated into data, the addresses are taken off, the packets are reconstructed and the data is rendered for the application.


![[tcpimage2.png]]