# Configuring IP Addresses and Routing — Cisco Packet Tracer

## 📄 Overview
This project demonstrates how to configure static IP addresses and implement basic routing between devices in Cisco Packet Tracer. It covers:
- Assigning IP addresses to multiple end devices and routers
- Subnetting and default gateway configuration
- Verifying end-to-end connectivity through routing setup

---

## 🖼 Topology
![Network Topology](pk1.png)

---

## ⚙️ Configuration Details

### 🔹 PC0
- **IP Address:** `192.168.1.2`
- **Subnet Mask:** `255.255.255.0`
- **Default Gateway:** `192.168.1.1`

![PC0 Configuration](pk2.png)

---

### 🔹 PC1
- **IP Address:** `192.168.2.2`
- **Subnet Mask:** `255.255.255.0`
- **Default Gateway:** `192.168.2.1`

![PC1 Configuration](pk3.png)

---

### 🔹 Router0
- **Interface g0/0:** `192.168.1.1`
- **Interface g0/1:** `192.168.2.1`

![Router Configuration](pk4.png)

---

## 📶 Connectivity Testing
Ping test from PC0 to PC1 confirms successful routing and IP configuration across networks.

![Ping Test](pk5.png)

---

## 📁 Files Included

| File                                | Description                                  |
|-------------------------------------|----------------------------------------------|
| `Configuring IP Addresses and Routing.pkt` | Cisco Packet Tracer file for the lab        |
| `pk1.png → pk5.png`                 | Screenshots of topology, configuration, ping |
| `README.md`                         | Documentation (this file)                    |

---

## ✅ Outcome
Each device was assigned a valid IP and default gateway. Static routing enabled communication across two networks, confirming proper setup of routing and IP configuration.

