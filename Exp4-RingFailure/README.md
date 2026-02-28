# Experiment 4 – Ring Topology Failure Test

## 🎯 Objective
To analyze fault tolerance by disconnecting one link in ring topology.

---

## 🛠 Configuration Details
- Same ring topology as Experiment 3
- One switch-to-switch link disconnected

---

## 🧪 Testing
1. Open `exp4 ring failure.pkt`
2. Disconnect one link
3. Run ping command
4. Observe behavior

---

## 📊 Observations
- Communication continues via alternate path.
- Fault tolerance exists as long as one path remains.
- Further failures may break network.

---

## 📂 Files Included
- exp4 ring failure.pkt
- exp4_output.txt
