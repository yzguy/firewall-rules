Firewall-Rules
==============

I wrote a quick and dirty firewall script in bash

There are 4 lines you will ever need to modify:
`tcp_ports_in=()`  
`tcp_ports_out=()`  
`udp_ports_in=()`  
`udp_ports_out()`  

Syntax: `tcp_ports_in=(80 443)`

Ports IN are the ports that need to be opened for services on your server to be access
`ex. Apache Webserver - TCP 80 443`

Ports OUT are for ports that you want to be able to access
`ex. HTTP - TCP 80`

SSH is allowed by default, so you don't accidently lock yourself out
Localhost interface, ICMP traffic, DNS outbound, are also allowed to provide basic functionality

After you have added the ports you need, then just run the script.
