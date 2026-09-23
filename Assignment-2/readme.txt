I prepared two Ubuntu Virtual Machines using Oracle VirtualBox. I configured both VMs to use the same NAT Network so that they could communicate with each other.

I checked the IP addresses of both VMs using the ip a command and used the ping command to verify connectivity between them. During the configuration, I found that the cloned Ubuntu VM had the same MAC address as the original VM, so I generated a new MAC address for the cloned VM. After this, both VMs received different IP addresses on the same network.

I designated one Ubuntu VM as the Server and the other as the Client. On the Server VM, I created and ran a TCP server program that listens for incoming connections. On the Client VM, I created a TCP client program that connects to the Server using its IP address and port number.

After establishing the TCP connection, I tested sending and receiving messages between the Server and Client. This demonstrated that the two Ubuntu VMs could communicate through the network and exchange messages using the TCP chat application.

Finally, I captured screenshots of the VirtualBox network configuration, IP addresses, successful ping test, and the TCP chat communication as evidence of the completed lab.

Result: Two Ubuntu VMs were successfully configured on the same NAT Network, connected using TCP, and used as a Server and Client to demonstrate a working chat application.