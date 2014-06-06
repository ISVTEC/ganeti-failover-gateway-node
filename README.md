ganeti-failover-gateway-node
============================

Manage Ganeti instances gateways on fail-over IP environment


This runs on each instance, it fetches a list of IP gateways from the ganeti master and uses the first that responds to an ARP query.


Tested at :
  * Online.net
  * OVH
