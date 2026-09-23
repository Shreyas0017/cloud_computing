I connected two Ubuntu virtual machines using a NAT Network
in Oracle VirtualBox.

First, I created a NAT Network in VirtualBox and assigned both Ubuntu
VMs to the same NAT Network. Initially, both VMs had the same MAC
address and received the same IP address because one VM was created as a
clone.

I fixed this by changing the MAC address of the Ubuntu Clone from the
VirtualBox network settings. After restarting both VMs, they received
different IP addresses in the same network, such as 10.0.2.15 and
10.0.2.16.

Finally, I used the ip a command to check the IP addresses and the
ping command to test communication between the two VMs. The ping was
successful, confirming that both Ubuntu VMs were connected and could
communicate through the NAT Network.

Result: Both Ubuntu virtual machines were successfully connected through
the same NAT Network.