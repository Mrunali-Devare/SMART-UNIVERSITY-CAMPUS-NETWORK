# 🎓 Smart University Campus Network Design (Cisco Packet Tracer)

A scalable and efficient campus network designed using Cisco Packet Tracer. This project simulates a real-world university network with multiple departments, VLAN segmentation, inter-VLAN routing, and cloud connectivity.

---

## ✨ Project Overview

The Smart University Campus Network is designed to provide secure and organized communication across different academic blocks and departments.

### 🏫 Includes:
- Block A (IT, CMPN, EXTC, EXCS)
- Block B (Faculty Departments)
- Block C (Student Labs & Servers)
- M Block (Staff & BMS Department)
- Cloud Network (Email Server)

---

## 🧠 Key Features

### 📡 VLAN Segmentation

| Department        | VLAN ID | Subnet            |
|------------------|--------|-------------------|
| IT Dept          | 10     | 192.168.1.0/24    |
| CMPN Dept        | 20     | 192.168.2.0/24    |
| EXTC Dept        | 30     | 192.168.3.0/24    |
| EXCS Dept        | 40     | 192.168.4.0/24    |
| FE Faculty       | 50     | 192.168.5.0/24    |
| All Faculty      | 60     | 192.168.6.0/24    |
| Student Labs     | 70     | 192.168.7.0/24    |
| Host Servers     | 80     | 192.168.8.0/24    |
| Staff            | 90     | 192.168.9.0/24    |
| BMS Dept         | 100    | 192.168.10.0/24   |

---

### 🔗 Inter-VLAN Routing
- Implemented using Multilayer Switch (Layer 3 Switch)
- Enables communication between VLANs

---

### 🌐 Routing Between Blocks
- Routers connect:
  - Main Campus Router
  - M Block Router
  - Cloud Router
- Static routing is used for communication

---

### ☁️ Cloud Integration
- Email server connected via cloud network
- Simulates external network access

---

### 🖥️ Server Infrastructure
- Web Server
- Exam Server
- Centralized access for users

---

### 🖨️ End Devices
- PCs and Printers in each department
- Connected through access switches (Cisco 2960)

---

## 🛠️ Technologies Used

- Cisco Packet Tracer
- Devices:
  - Cisco 2911 Routers
  - Cisco 2960 Switches
  - Cisco 3650 Multilayer Switch
- Networking Concepts:
  - VLAN
  - Inter-VLAN Routing
  - Subnetting
  - Static Routing

---

## 📂 Network Architecture

### 🏢 Block A
- IT, CMPN, EXTC, EXCS Departments

### 🏢 Block B
- FE Faculty
- All Faculty

### 🏢 Block C
- Student Labs
- Servers

### 🏢 M Block
- Staff
- BMS Department

---

## 🚀 How to Run

1. Open Cisco Packet Tracer
2. Load the `.pkt` file
3. Wait for all devices to initialize
4. Use Simulation Mode or CLI to test

---

## 💻 Usage

- Test connectivity using `ping`
- Verify:
  - VLAN configuration
  - IP addressing
  - Routing tables
- Access servers from different VLANs

---

## 📊 Learning Outcomes

- Understanding campus network design
- VLAN and subnetting concepts
- Routing and switching fundamentals
- Network simulation and troubleshooting

---

## 👩‍💻 Team Members

**Class / Batch:** INFT B

| Name | Roll No |
|------|--------|
| Mrunali Devare | 24101B0032 |
| Himanshu Choyal | 24101B0035 |
| Sarthak Kane | 24101B0030 |

---

## 📌 Future Enhancements

- Implement ACL (Access Control Lists)
- Add Wireless Network (Wi-Fi)
- Use Dynamic Routing (OSPF/EIGRP)
- Add Network Security Features

---

## 📎 File

- `campus_project.pkt` → Cisco Packet Tracer file
