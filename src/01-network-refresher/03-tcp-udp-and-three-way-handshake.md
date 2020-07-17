
# TCP, UDP and three way shake

This is now layer 4, the transport layer of the OSI model.

TCP is more reliable and connection oriented.

UDP is connectionless.

We're going to be scanning both TCP and UDP.

## TCP's Three way handshake

I send a SYN packet.  
Then I receive a SYN ACK packet.  
Then I send a ACK packet.

Each of these are sent from a port and to a port.

We can use wireshark to see the handshake in action.

We can modify the handshake so we can make it scan.
