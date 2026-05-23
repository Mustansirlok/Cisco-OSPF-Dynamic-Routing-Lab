# Cisco OSPF Dynamic Routing Lab

## Project Overview

This project demonstrates the implementation of OSPF (Open Shortest Path First) dynamic routing in a multi-router enterprise network using Cisco Packet Tracer. The network was designed to enable communication between multiple remote networks through automatic route learning and dynamic routing updates.

The lab simulates a real-world enterprise routing environment where routers exchange routing information to establish end-to-end connectivity between hosts located on different networks.

---

## Technologies and Concepts Used

- Cisco Packet Tracer
- OSPF Routing Protocol
- Dynamic Routing
- IP Addressing
- Multi-Router Connectivity
- Cisco IOS CLI
- Network Verification and Troubleshooting

---

## Network Features

### OSPF Dynamic Routing
Configured OSPF routing between routers to dynamically advertise and learn remote network routes.

### Router Interface Configuration
Assigned IP addresses to router interfaces according to the provided topology.

### Host IP Addressing
Configured IP addressing on end devices to enable communication across routed networks.

### Dynamic Route Learning
Enabled routers to automatically exchange routing information and maintain updated routing tables.

### End-to-End Connectivity
Established successful communication between hosts located on different networks using OSPF routing.

---

## Verification and Testing

The following verifications were successfully completed:

- OSPF routing configuration verification
- Dynamic route learning verification
- Router interface verification
- Routing table analysis
- Successful end-to-end connectivity testing
- Inter-network communication validation

---

## Verification Commands Used

```bash
show running-config
show ip route
show ip protocols
show ip interface brief
ping [destination-ip]
```

---

## Project Structure

```text
Cisco-OSPF-Dynamic-Routing-Lab/

├── README.md
├── ospf-routing-lab.pkt
├── topology.png

└── screenshots/
    ├── ospf-config.png
    ├── show-ip-route.png
    ├── ip-protocols.png
    ├── router-interfaces.png
    └── end-to-end-ping.png
```

---

## Skills Demonstrated

- OSPF dynamic routing implementation
- Enterprise routing concepts
- Router configuration
- Dynamic route learning
- Cisco CLI configuration
- IP addressing and subnetting
- Network troubleshooting
- Routing verification and testing

---

## Author

Mustansir Lokhandwala
