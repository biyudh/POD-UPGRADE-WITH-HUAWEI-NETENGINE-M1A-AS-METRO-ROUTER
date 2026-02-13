


# 🛰️ Project: POD Upgrade with Huawei NetEngine M1A as Metro Router

## 📸 Network Diagram  

<img width="1587" height="769" alt="image" src="https://github.com/user-attachments/assets/cb71228a-9903-478a-be4c-4dfe9bf1754f" />

## 📘 Overview  
This project involved a **real-world production network upgrade** to enhance the metro network architecture using **Huawei NetEngine 8000 M1A** as the **Metro Router**.  
The goal was to optimize traffic engineering, improve redundancy, and enable efficient service delivery through **MPLS and OSPF-based routing integration**.

---

## 🧑‍💻 Role & Team Structure  

**Role:** NOC Engineer  
**Team Size:** 6 Members  
- 1 × NOC Engineer *(My Role)*  
- 1 × Network Support Engineer  
- 2 × Fiber Technicians  
- 2 × Electrical Team Members  

**Duration:** `30th June 2025 – 1st July 2025`  
**Project Type:** Live Metro Network Upgrade (Production Environment)

---

## 🧩 Network Architecture  

### 🔹 Project Segments  

#### 1️⃣ Metro Segment (POD Upgrade Site)
- Huawei **NetEngine 8000 M1A** as Metro Router  
- Connected downstream to **EA5800X2 Huawei OLT**  
- End-user connectivity via **Client ONT/Access Point**

#### 2️⃣ Core Network & Internal Infrastructure
- **Core Router** integrated with Metro Router via MPLS LDP  
- **BNG (Broadband Network Gateway)** for subscriber management  
- **IGW (Internet Gateway)** for upstream connectivity  
- **CDN Nodes (FNA/GGC)** connected to improve local content delivery  

## ⚙️ Configuration Highlights  

### 🔸 MPLS & OSPF Integration  
- Enabled **MPLS LDP** for label distribution and high-speed forwarding.  
- Configured **OSPF** for dynamic route advertisement across metro and core domains.  
- Implemented **Traffic Engineering (MPLS-TE)** for load balancing and redundancy.  

### 🔸 VLANs & VSIs  
- Designed **VLAN segmentation** for service isolation (Business, Home, Internal).  
- Created **VSI instances** for virtual service interfaces, supporting multiple customer services over shared infrastructure.  

### 🔸 Core Integration  
- Established **LDP sessions** between **Metro Router** and **Core Router** for label exchange.  
- Configured **redundant links** to ensure failover protection and path diversity.  

### 🔸 Management & Security  
- Configured **SNMP** for network monitoring and performance tracking.  
- Deployed **TACACS+** for centralized authentication and authorization.  
- Enabled **LLDP** for topology discovery and neighbor management.  
- Implemented **LACP** for link aggregation between critical devices.  
- Configured **NTP** synchronization across routers and OLT for clock accuracy.  

---

## 🧠 Technologies Used  

| Category | Technology / Protocol |
|-----------|----------------------|
| Router Platform | Huawei NetEngine 8000 M1A |
| Optical Platform | Huawei EA5800X2 OLT |
| Routing Protocol | OSPF |
| MPLS | LDP, Traffic Engineering (TE) |
| Layer 2 | VLAN, VSI, LACP |
| Management | SNMP, LLDP |
| Authentication | TACACS+ |
| Time Sync | NTP |

---

## 🔍 Key Outcomes  
✅ Upgraded the metro segment with high-capacity Huawei M1A routers  
✅ Achieved faster convergence with OSPF + MPLS LDP integration  
✅ Improved redundancy and traffic handling efficiency  
✅ Enhanced visibility and security via SNMP, LLDP, and TACACS+  
✅ Strengthened user experience with optimized local CDN access  

---

---

## 🏁 Summary  
This **Metro Router Upgrade Project** modernized the existing access and aggregation layers with Huawei’s **NetEngine 8000 M1A**, ensuring a scalable, resilient, and service-oriented metro network architecture.  
The deployment successfully integrated with the **core, BNG, IGW, and CDN**, delivering improved user performance and streamlined management.

---




