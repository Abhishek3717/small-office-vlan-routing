
# 🖥️ Small Office Network with 3 VLANs and Inter-VLAN Routing

This project demonstrates the design and configuration of a small office network using VLANs and router-on-a-stick inter-VLAN routing. The network is segmented into three departments—Admin, Accounts, and HR—each assigned a unique VLAN with proper subnetting and gateway configuration.

---

## 📁 Files Included

- `Project_VLAN_3Dept_NetworkDesign.pdf` – Detailed project documentation with steps and configurations.
- `project.pkt` – Cisco Packet Tracer file .

---

## 🔧 Devices Used

- Cisco Router (e.g., 2811)
- Cisco Switch (e.g., 2960 - Layer 2)
- 6 PCs assigned to different VLANs

---

## 🧩 VLAN Setup

| Department | VLAN ID | Network/Subnet     | Devices  |
|------------|---------|---------------------|----------|
| Admin      | 10      | 192.168.10.0/24     | PC0, PC1 |
| Accounts   | 20      | 192.168.20.0/24     | PC2, PC3 |
| HR         | 30      | 192.168.30.0/24     | PC4, PC5 |

---

## 🛠️ Configuration Highlights

- VLAN creation and assignment on switch
- Trunk port setup for router connection
- Inter-VLAN routing using router-on-a-stick method
- Static IP and gateway assignment to each PC
- End-to-end connectivity verification via ping tests

---

## 📌 Concepts Demonstrated

- VLANs and subnetting
- Trunk links and access ports
- Router-on-a-stick inter-VLAN routing
- Basic Cisco CLI configuration
- Network testing with ICMP

---

## ✅ How to Use

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Follow the configuration steps in the PDF or use the pre-configured setup.
3. Run connectivity tests between VLANs to verify inter-VLAN routing.
