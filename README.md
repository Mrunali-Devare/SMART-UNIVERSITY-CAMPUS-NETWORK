🎓 Smart University Campus Network Design (Cisco Packet Tracer)

A comprehensive campus-wide network design built using Cisco Packet Tracer, simulating a real-world university infrastructure. This project demonstrates scalable, secure, and efficient network architecture using VLANs, routing, and centralized services.

✨ Project Overview

This project models a multi-block university campus network consisting of:

🏫 Academic Blocks (A, B, C)
🧑‍🏫 Faculty & Staff Departments
🧪 Student Labs
🖥️ Server Infrastructure
☁️ Cloud Connectivity (Email Server)

The design ensures:

Efficient communication between departments
Logical segmentation using VLANs
Secure and optimized routing across the campus
🧠 Key Features
📡 VLAN Segmentation

Each department is assigned a separate VLAN for better security and traffic management:

Department	VLAN ID	Subnet
IT Dept	10	192.168.1.0/24
CMPN Dept	20	192.168.2.0/24
EXTC Dept	30	192.168.3.0/24
EXCS Dept	40	192.168.4.0/24
FE Faculty	50	192.168.5.0/24
All Faculty	60	192.168.6.0/24
Student Labs	70	192.168.7.0/24
Host Servers	80	192.168.8.0/24
Staff	90	192.168.9.0/24
BMS Dept	100	192.168.10.0/24
🔗 Inter-VLAN Routing
Implemented using Multilayer Switch (Layer 3 Switch)
Enables communication between different VLANs
🌐 Routing Between Blocks
Routers connect:
Main Campus
M Block
Cloud Network
Uses static routing (or dynamic if implemented)
☁️ Cloud Integration
External Email Server connected via cloud
Simulates real-world internet services
🖥️ Server Infrastructure
Dedicated VLAN for servers:
🌐 Web Server
📝 Exam Server
Centralized access for students and staff
🖨️ Network Devices
Each department includes:
PCs
Printers
Connected via access switches (2960)
🛠️ Technologies Used
🧰 Cisco Packet Tracer
🔌 Networking Devices:
Routers (Cisco 2911)
Switches (2960, 3650 Multilayer)
🌐 Concepts Implemented:
VLANs
Inter-VLAN Routing
Subnetting
Static Routing
Network Segmentation
📂 Network Architecture
🏢 Block A
IT, CMPN, EXTC, EXCS Departments
Separate VLANs for each
🏢 Block B
FE Faculty
All Faculty
🏢 Block C
Student Labs
Host Servers
🏢 M Block
Staff
BMS Department
🚀 How to Run the Project
Open Cisco Packet Tracer
Load the .pkt file
Wait for devices to initialize
Use:
Simulation Mode to observe packet flow
Ping commands to test connectivity
💻 Usage
Test communication:
Between different VLANs
Between blocks
Access servers from student PCs
Verify:
Routing tables
VLAN configurations
IP addressing
📊 Learning Outcomes
Understanding of real-world campus network design
Hands-on practice with:
VLAN configuration
Routing concepts
Network scalability
Improved troubleshooting and simulation skills
👩‍💻 Team Details

Class / Batch: INFT B

Name	          Roll Number
Mrunali Devare	24101B0032
Himanshu Choyal 24101B0035
Sarthak Kane    24101B0030
