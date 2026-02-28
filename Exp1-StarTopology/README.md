# Experiment 1 – Star Topology (Switch)

## 🎯 Objective
To design a LAN using Star Topology with a switch and verify connectivity using IPv4 addressing and ICMP ping.

---

## 🛠 Configuration Details
- 1 Switch (2960)
- 4 PCs
- IP Address Range:
  - 192.168.10.1
  - 192.168.10.2
  - 192.168.10.3
  - 192.168.10.4
- Subnet Mask: 255.255.255.0

---

## 🧪 Testing
1. Open `exp1 star topology.pkt`
2. Click PC → Desktop → Command Prompt
3. Run:
   ping 192.168.10.X

All devices successfully communicate.

---

## 📊 Observations
- Switch forwards packets only to the intended device.
- Communication is fast and collision-free.
- If one PC fails, rest of the network works.
- If switch fails, entire network stops.

---

## 📂 Files Included
- exp1 star topology.pkt
- exp1_output.txt
