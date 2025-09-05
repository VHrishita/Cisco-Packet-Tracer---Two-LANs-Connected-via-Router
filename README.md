# Cisco-Packet-Tracer---Two-LANs-Connected-via-Router
This project demonstrates how to interconnect two separate Local Area Networks (LANs) using routers in Cisco Packet Tracer. Each LAN contains multiple end devices connected through a switch, and both are connected to a central router for communication between networks.

# Interconnecting Two LANs using Routers in Cisco Packet Tracer

## 📝 Project Overview

This project demonstrates how to interconnect two separate Local Area Networks (LANs) using routers in Cisco Packet Tracer. Each LAN contains multiple end devices connected through a switch, and both are connected to a central router for communication between networks.

## 🧰 Tools Used

- Cisco Packet Tracer
- Basic networking components:
  - Routers
  - Switches
  - PCs
  - Ethernet cables

## 🌐 Network Design

- **LAN 1**:
  - Switch
  - Multiple PCs
  - IP range: `192.168.1.0/24`

- **LAN 2**:
  - Switch
  - Multiple PCs
  - IP range: `192.168.2.0/24`

- **Router**:
  - Interfaces configured for each LAN
  - Static routes or RIP (if configured)

## ⚙️ Configuration Steps

1. Assign IP addresses to all PCs and router interfaces.
2. Configure default gateways for all PCs.
3. Configure static routes on the router (or dynamic routing protocol).
4. Test connectivity using the `ping` command from one LAN to another.

## ✅ Outcomes

- Devices within each LAN can communicate locally.
- Devices from LAN 1 can successfully ping devices in LAN 2 and vice versa.
- Router properly routes traffic between both networks.

## 📁 File Included

- `Two Lans.pkt`: Cisco Packet Tracer file demonstrating the setup.

## 📸 Preview

_A screenshot or diagram can be added here to visualize the topology._

## 💡 Future Enhancements

- Add DHCP server for automatic IP addressing.
- Implement Access Control Lists (ACLs) for traffic filtering.
- Simulate internet access through an ISP router.

---
