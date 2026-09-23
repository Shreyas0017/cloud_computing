I installed Mininet in my Ubuntu virtual machine using the installation instructions from the Mininet website. After installation, I checked the Mininet version using the command sudo mn --version.

I then tested the basic Mininet network using sudo mn --test pingall. The test created two hosts and a switch, and the hosts were able to communicate successfully.

Next, I created a single-switch topology with three hosts using sudo mn --topo single,3. I used the links command to check the connections between the hosts and switch, and then used pingall to test connectivity between all three hosts. The connectivity test was successful.

After that, I created a tree topology using sudo mn --topo tree,3. I checked the network connections using the links command and tested communication between the hosts using pingall. The hosts were able to communicate successfully.

Finally, I exited Mininet after completing the topology and connectivity tests. I captured screenshots of the Mininet commands, network connections, and successful ping tests for my lab record.
