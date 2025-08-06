# Configuring IP Addresses and Routing — Cisco Packet Tracer

## 📄 Overview

This project demonstrates how to configure IP addresses and dynamic routing between two routers using RIP version 2 in Cisco Packet Tracer. The network consists of two routers, two PCs, and two switches. The objective is to enable end-to-end connectivity through proper IP addressing and routing protocol setup.

This lab follows the step-by-step structure provided in *Network+ Learning Activity #10*, and includes static IP configuration on both routers and PCs, as well as the implementation of RIPv2 to enable communication across subnets.

---

## 🖼️ Topology

The network consists of:
- **Router0** (Left)
- **Router1** (Right)
- **PC0** (Connected to Router0)
- **PC1** (Connected to Router1)
- **Two switches** (for LAN connection to PCs)

![Network Topology](tt1.png)

---

## ⚙️ Router Configuration

### 🔹 Router0

1. **Interface GigabitEthernet0/0**
   - IP: `200.5.5.1`
   - Subnet Mask: `255.255.255.192`
2. **Interface Serial0/0/0**
   - IP: `200.5.5.65`
   - Subnet Mask: `255.255.255.192`

![Router0 - G0/0 Config](tt2.png)  
![Router0 - Serial Config](tt3.png)

#### 🔄 RIP Configuration on Router0
- RIP Version: 2
- Network: `200.5.5.0`

Commands used:
```bash
router rip
version 2
network 200.5.5.0
