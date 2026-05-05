# Small Business Network Lab

## 🌐 Network Topology
![Topology](screenshots/topology.png)

## 🎯 Skills Demonstrated
- VLAN configuration
- Subnetting and IP addressing
- Inter-VLAN routing (Router-on-a-Stick)
- Network troubleshooting (ping, tracert)
- Switch and router configuration

## ⚙️ How It Works

- Each department is assigned a VLAN
- VLANs separate the network into different broadcast domains
- A trunk link connects the switch to the router
- The router uses subinterfaces to route traffic between VLANs
- Devices use default gateways to communicate across networks

## 📌 Overview
This project simulates a small business network with three departments:
- Sales
- Admin
- IT

The network uses VLANs and inter-VLAN routing to allow communication between departments.

---

## 🧪 Testing Results

### Ping Test: Sales to Admin
![Ping](testing-results/ping-sales-to-admin.png)
