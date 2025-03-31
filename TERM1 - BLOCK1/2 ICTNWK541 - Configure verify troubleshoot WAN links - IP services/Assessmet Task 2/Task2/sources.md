enable 
configure terminal
hostname rt1
ipv6 unicast-routing 

interface gigabitEthernet 0/0
ipv6 address 2000::1/64
no shutdown 
ipv6 dhcp pool STATEFUL_POOL
domain-name milestones.com
dns-server 2000::10
prefix-delegation pool STATEFUL_POOL
exit
interface gigabitEthernet 0/0 
ipv6 dhcp server STATEFUL_POOL
ipv6 nd managed-config-flag
exit
do wr
exit
exit



Sources
- Network System, Secure Company: https://www.youtube.com/watch?v=Cbv95OxT1FM
- DHCPv6 Router: https://www.youtube.com/watch?v=HQbQuXxqXSo
- DHCPv6 stateless-stateful: https://computernetworking747640215.wordpress.com/2019/11/05/configuring-dhcpv6-both-stateless-and-stateful-in-packet-tracer/
- ACLs: https://www.packettracernetwork.com/tutorials/packet-tracer-acls.html
