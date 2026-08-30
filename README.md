# Cisco Packet Tracer - Static Routing

## 📌 Project Overview

This project demonstrates the configuration of **Static Routing** using Cisco Packet Tracer.

The network consists of three routers connected through different networks, with multiple LANs containing switches and PCs.

The main objective is to configure static routes so that all devices in the different networks can communicate with each other.

## 🌐 Network Topology

The topology contains:

- 3 Cisco Routers
- 4 Cisco Switches
- Multiple PCs
- Router-to-Router connections
- Multiple LAN networks
- Static routing configuration

### Routers

- Router0
- Router1
- Router2

### Networks

| Network | Purpose |
|---|---|
| 10.0.0.0 | Router0 LAN |
| 172.16.0.0 | Router0 LAN |
| 2.0.0.0 | Router0 ↔ Router1 |
| 3.0.0.0 | Router1 ↔ Router2 |
| 192.168.0.0 | Router1 LAN |
| 192.168.1.0 | Router2 LAN |
| 4.0.0.0 | Shared network between Router0 and Router2 |

## 🔢 IP Addressing

### Router0

- `10.0.0.1`
- `172.16.0.1`
- `2.0.0.1`
- `4.0.0.1`

### Router1

- `2.0.0.2`
- `3.0.0.1`
- `192.168.0.1`

### Router2

- `3.0.0.2`
- `4.0.0.2`
- `192.168.1.1`

## ⚙️ Routing Configuration

Static routes are configured manually on the routers using the Cisco IOS command:

```bash
ip route <destination-network> <subnet-mask> <next-hop>
```

## 🧪 Connectivity Testing

After configuring the static routes, connectivity can be tested using:

```bash
ping <destination-ip>
```

The routing table can be checked using:

```bash
show ip route
```

Static routes are identified by:

```text
S
```

## 🎯 Project Objectives

This project was created to practice:

- IPv4 addressing
- Network topology design
- Router configuration
- Static routing
- Next-hop configuration
- Routing table analysis
- Network connectivity testing
- Basic troubleshootingg


## 🛠️ Tools Used

- Cisco Packet Tracer
- Cisco IOS
- IPv4
- Static Routing


## 📁 Project File

The complete Packet Tracer project is available in:

```text
Static Routing.pkt

