# Advanced-Computer-Networks
LAN and WAN designs, the final project of the Advanced Computer Networks course at IIIT Hyderabad. We showcase our LAN design in `LAN.pdf`, and our WAN design in `WAN.pdf`. 

### LAN Design
Design LAN for the locality you are staying right now - Apartment/Township/Colony/Village/Hostel/etc. You need to address the following aspects:

- Topological design
- Choice of cables at various levels
- Choice of switching devices - types/category of the device, port speed, L2/L3
- IP Addressing schema

State your assumptions, justify your choices. A detailed design is expected, discussing the specifics of each aspect/component required for implementing the LAN.

### WAN Design
You are a group of 3 students. You have designed LAN for the locality you are staying right now. Now do the following:

- Plan to connect LANs that belong to your group members. Decide which services should be accessible and which ones to be restricted across these three LAN.

- Houses and public places in your localities must have been provided services such as electricity, water, LPG pipelines connection, sewerage and some other utility connections. Plan to make provision for an on-line metering and monitoring of these utility services provided by connecting to Electricity Board/Power Distribution companies, Municipality, Panchayat, etc. systems. Work out design and details.

- Plan to install and connect security systems (intruder detection, fire alarms, seismic sensors, etc) with the nearest police station, Fire Brigade office, etc.

While designing, sizing and detailing the required network connectivity, address issues related to information security, reliability and availability in times of natural calamities (floods, etc). List out options explored and give reasons for the choices made.

### DVMRP
Make a short presentation on the Distance Vector Multicast Routing Protocol, for class presentation.

This RP is used to share information between routers to facilitate the transportation of IP multicast packets among networks. It formed the basis of the Internet's historic multicast backbone, Mbone. The protocol is based on the Routing Information Protocol (RIP). The router generates a routing table with the multicast group of which it has knowledge with corresponding distances (i.e. number of devices/routers between the router and the destination). When a multicast packet is received by a router, it is forwarded by the router's interfaces specified in the routing table.

