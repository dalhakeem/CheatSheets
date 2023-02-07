# Networking Commands Cheatsheet

## Display IP address

ifconfig




## Display active network connections

netstat -an




## Ping a host

ping <hostname/ip>




## Traceroute to a host

traceroute <hostname/ip>

css


## Display routing table

route -n




## Display network interfaces

ip addr show




## Display DNS information

cat /etc/resolv.conf




## Add a new route

route add <destination_network> gw <gateway_ip>




## Delete a route

route del <destination_network> gw <gateway_ip>




## Enable/disable a network interface

ifconfig <interface> up/down




## Configure IP address for an interface

ifconfig <interface> <ip_address>




## Configure network mask for an interface

ifconfig <interface> netmask <network_mask>