# 🏢 Tech Solutions Network Design Proposal

Welcome, Network Engineer! 🚀  
You're hired to design a scalable and efficient network infrastructure for **Tech Solutions**, a mid-sized enterprise with a 5-floor office building. Below are the requirements and constraints for building the network.

---

## 🏗️ Network Design Requirements

### 1️⃣ Topology Selection
- 🟢 **Star Topology** for **Floors 1 to 4** for simplicity, performance, and ease of troubleshooting.
- 🔷 **Mesh Topology** for **Floor 5** for enhanced **fault tolerance** and **redundancy**.
- ⚠️ **Note:** Due to Cisco Packet Tracer limitations, connect only **7 computers per floor** for simulation.

---

### 🌐 IP Addressing Scheme
- ✅ Use **Class A Private IPv4 Addresses** with **VLSM** for:
  - Floor 1 🧮 (DHCP Server)
  - Floor 2 🌐 (HTTP Server)
  - Floor 3 📧 (Email Server)
- 🌍 Use **Class A Public IPv4 Addresses** with **VLSM** for:
  - Floor 4 🖥️ (Clients)
  - Floor 5 📁🔍 (FTP & DNS Servers)
- Ensure each floor has **unique subnets** for efficient IP management and no address conflicts.

---

### 🔄 Routing Strategy
- Use **Dynamic Routing Protocols** (e.g., RIP, OSPF, or EIGRP) to enable:
  - 📡 Seamless **inter-floor communication**
  - 🔁 **Scalability** for future expansion
  - 🔄 **Automatic route updates** without manual reconfiguration

---

## 🛠️ Server Placement
| Floor | Devices / Services       |
|-------|--------------------------|
| 1️⃣    | 💻 DHCP Server           |
| 2️⃣    | 🌐 HTTP Server           |
| 3️⃣    | 📧 Email Server          |
| 5️⃣    | 📁 FTP & 🔍 DNS Servers |

---

> ⚙️ Design your network in **Cisco Packet Tracer** adhering to the above specifications for simulation and deployment.
