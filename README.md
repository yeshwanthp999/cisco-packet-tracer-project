# Cisco Packet Tracer Networking Project

This project simulates a small-scale network using **Cisco Packet Tracer**. The topology consists of multiple switches, a router, PCs, and a server configured across four different subnets.

## 📁 Project Overview

The network is segmented into four subnets:

- **192.168.1.0/24** – Server network (SW2)
- **192.168.2.0/24** – PC network (SW1)
- **192.168.3.0/24** – PC network (SW3)
- **192.168.4.0/24** – PC network (SW4)

All devices are connected via a central router (`R1`) to enable inter-VLAN or inter-subnet communication.

## 🖧 Network Topology

PCs <--> SW1 <--> <--> SW2 <--> Server (192.168.1.100)
\ | /
\ Router (R1)
\ |
--> SW3 <--> PCs (192.168.3.x)
--> SW4 <--> PCs (192.168.4.x)

markdown
Copy
Edit

## 🔧 Configuration Highlights

- **Router (R1)**:
  - Interfaces configured with IPs:  
    - `192.168.1.1`  
    - `192.168.2.1`  
    - `192.168.3.1`  
    - `192.168.4.1`
  - Routing enabled to allow communication between subnets.

- **Switches (SW1–SW4)**:
  - Each switch handles traffic for one subnet.
  - Basic switch configurations; no VLAN segmentation applied in this setup.

- **End Devices**:
  - All PCs and server are assigned static IPs as per their respective subnets.

## 🎯 Objectives

- Build a basic routed network in Packet Tracer
- Test connectivity between PCs and the server across different subnets
- Practice router interface and IP configuration
- Understand inter-subnet routing

## ✅ Ping Test

Ensure the following:
- All PCs can successfully ping the server (`192.168.1.100`)
- Devices can communicate across different subnets
- Proper IP configuration on all router interfaces and end devices

## 📂 File Contents

- `.pkt` file (Cisco Packet Tracer simulation)
- `README.md` (project documentation)

## 🚀 How to Open

1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Open the `.pkt` file in Packet Tracer.
3. Start simulation or real-time mode to test connectivity.

---

## 💡 Author

- **Name**: Yeshwanth Parvathaneni  
- **GitHub**: [yeshwanthp999](https://github.com/yeshwanthp999)

---

## 📌 Note

This project is designed for educational and learning purposes to demonstrate basic routing concep
