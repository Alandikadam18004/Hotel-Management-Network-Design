# Hotel-Management-Network-Design
# 🏨 Hotel Network Infrastructure – CCNA Project (Cisco Packet Tracer)

## 📘 Project Overview

This project simulates the **network infrastructure of a 3-floor hotel** using Cisco Packet Tracer. It focuses on designing a **segmented, secure, and scalable network**, incorporating VLANs per department, DHCP for IP management, wireless connectivity, and secure remote access using SSH.

---

## 🧱 Network Layout

### 🏢 Floor-wise VLAN & Device Structure

#### 🔹 First Floor
- **VLAN 80 – Reception**
- **VLAN 70 – Store**
- **VLAN 60 – Logistics**
- 1 PC + 1 Printer per VLAN
- 1 Wireless Access Point
- 1 Switch
- 1 Router (Connected to other floor routers via RIP)

#### 🔹 Second Floor
- **VLAN 30 – Sales**
- **VLAN 40 – HR**
- **VLAN 50 – Finance**
- 1 PC + 1 Printer per VLAN
- 1 Wireless Access Point
- 1 Switch
- 1 Router

#### 🔹 Third Floor
- **VLAN 10 – IT**
- **VLAN 20 – Admin**
- 1 PC + 1 Printer per VLAN
- 1 Wireless Access Point
- 1 Switch
- 1 Router

---

## ⚙️ Technical Features Implemented

| Feature | Description |
|--------|-------------|
| ✅ VLAN Configuration | Each department on its own VLAN |
| ✅ DHCP | Centralized IP assignment for all PCs and printers |
| ✅ DNS | Simulated DNS server for name resolution |
| ✅ RIP | Routing between floor routers using RIP protocol |
| ✅ Inter-VLAN Routing | Allows communication across departments |
| ✅ SSH | Secure remote management of routers/switches |
| ✅ Port Security | Sticky MAC configuration to restrict unauthorized access |
| ✅ Wireless Access | Access Points deployed on each floor for connectivity |

---

## 🧪 Testing & Validation

- ✅ Devices on same VLAN can communicate (e.g., Reception PC ↔ Printer)
- ✅ Inter-VLAN routing successful (e.g., Admin PC ↔ HR PC)
- ✅ All devices receive IP via DHCP
- ✅ RIP routes exchanged between floor routers
- ✅ DNS lookup successful
- ✅ SSH access to routers/switches tested and verified
- ✅ Unauthorized MAC address blocked via Port Security

---

## 📁 Files Included

- `project2.pkt` – Cisco Packet Tracer simulation file
- `hoteltopology.png` – Screenshot of the floor-based topology
- `Project_report.pdf`- Documentation
---

## 💼 Skills Demonstrated

- VLANs and Subnetting  
- DHCP & DNS Configuration  
- RIP Routing Protocol  
- Inter-VLAN Routing  
- SSH & Port Security  
- Wireless Networking  
- Layer 2 & Layer 3 Cisco IOS Commands  

---

## 📫 Contact

📧 Email: alandikadam2@gmail.com


---

