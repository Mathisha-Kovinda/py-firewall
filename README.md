In this project, I am building a firewall using python and its in-built libraries. Firewall is an essential part of network security between public and private network barriers to control incoming and outgoing traffic. This project focuses on creating a zone-based firewall, 
which manages traffic by assigning different interfaces to different interfaces and controlling each zone separately with specific security policies. Normally one zone represents one segment of the network. This project takes some aspects of a genuine zone-based firewall 
some features maybe not available that is in a genuine zone-based firewall.

Features


• Logs.
• Static Nat. 
• IDS. 
• Site to Site VPN. 
• Traffic monitoring and control according to zones.



Limitations 

• Some aspects of a zone-based firewall are not included. 
• Only capable of static NAT. 
• Not having an efficient way to install in another host. 
• Because of working with iptables and nftables not ideal to implement a large scale 
  due to the methods how the firewall handles adding and deleting rules. 
• VPN tunnel may be inconsistent. 
• Performance issues when coming to medium or large scale. 
• No reverse or forward proxy. 
• One interface should always be limited to one network. 
• Demo logging system. 

Future Implementations 

• Adjust to support multiple networks in one interface. 
• Ability to implement port address translation (PAT). 
• Using docker to create a container for this firewall to run. 
• Using an ideal way to handle routing and firewall rules and making the deleting 
  process, adding process more efficient. 
• Adding an option for rule modification. 
• Performance efficiency to handle large traffic. 
• Robust logging system. 
• Proxy services.
