firewall-rules
==============

Quick and Dirty IPtables firewall script

All you need to do is modify

`tcp_ports_in=()`
`tcp_ports_out=()`
`udp_ports_in=()`
`udp_ports_out()`

Adding in the ports you wish to open in the `()`, separated by a space,
then just run the script

Localhost, ICMP, DNS, SSH are all allowed by default
