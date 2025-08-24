# NUCES SDN Project – Computer Networks

This project simulates a **Software-Defined Networking (SDN)** environment using **Cisco Packet Tracer** for a multi-campus network.  
It was developed as part of the **Computer Networks (Spring 2025)** course under **Dr. Usman Habib** at **FAST-NUCES, Islamabad**.

---

## 📊 Overview
The project demonstrates SDN principles such as:
- Centralized controller-based management
- Scalable IP addressing across campuses
- Traffic engineering using ACLs
- Load balancing between multiple edge servers
- Backup network for redundancy

The network spans **six campuses (Islamabad, Karachi, Lahore, Faisalabad, Peshawar, Multan)** connected to a **Head Office**.

---

## 🏗️ Project Components

### 🔹 Part 1 – Planning & Design
- Designed a structured **network topology** with head office + six campuses.  
- Created a **scalable IP addressing scheme** (`10.0.x.0/24` per campus).  
- Planned SDN features: centralized control, traffic engineering, load balancing.

### 🔹 Part 2 – Network Setup & Configuration
- Built topology in **Cisco Packet Tracer** with routers, switches, PCs, and servers.  
- Assigned IPs and default gateways.  
- Verified connectivity with **ping tests**.  

### 🔹 Part 3 – SDN Controller Logic
- Configured static routing for **inter-campus connectivity**.  
- Implemented a **backup network (10.0.20.0/24)** for redundancy.  
- Enabled centralized control via the **HeadOffice-Controller**.

### 🔹 Part 4 – Traffic Engineering & Load Balancing
- Applied **ACLs** to allow server traffic and block PC-to-PC cross-campus communication.  
- Implemented **load balancing** using a virtual loopback service IP (`10.0.40.1`) to distribute traffic across two head office servers.  

---

## 🛠️ Tools & Technologies
- **Cisco Packet Tracer**
- **Static Routing, ACLs, Load Balancing**
- **IP Addressing Scheme (/24 subnets)**

---

## 👨‍💻 Contributors
- **Abdullah Daoud (22I-2626)**  
- **Usman Ali (22I-2725)**  
- **Faizan Rasheed (22I-2734)**  

---

## 📅 Course Information
- **Course**: Computer Networks (Spring 2025)  
- **Instructor**: Dr. Usman Habib  
- **Department**: Software Engineering, FAST-NUCES Islamabad  

---

## ⚖️ License
This project is for **academic purposes only**.  
Reuse is allowed for **learning and research** with proper credit.

---
