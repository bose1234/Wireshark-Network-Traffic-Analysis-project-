# Wireshark Network Traffic Analysis

## 📌 Project Overview
This project demonstrates how to capture and analyze live network traffic using **Wireshark**. The goal was to identify normal network patterns and detect any unusual or potentially suspicious packets.

---

## 🛠️ Tools & Methodology
- **Tool Used:** Wireshark (latest version)
- **Process:**
  1. Captured 5 minutes of live Wi-Fi traffic.
  2. Applied filters (`http`, `dns`, `tcp.port==445`) to analyze specific protocols.
  3. Identified normal vs. unusual traffic patterns.

---

## 🔍 Key Findings
### ✅ Normal Traffic
- **TCP Port 80 (HTTP):** Regular web browsing activity (PSH, ACK flags).

### ⚠️ Suspicious Traffic
- **Example:** Unusual DNS or SMB traffic detected (could expose the system to scanning or exploitation if left unmonitored).

*(See full PDF report for details)*

---

## ✅ Recommendations
- Monitor network traffic regularly for abnormal activity.
- Disable unnecessary services (e.g., SMB) if not required.
- Keep all devices updated with security patches.

---

## 📄 Deliverables
- **Wireshark Network Traffic Analysis Report (PDF)**
- **Normal & Suspicious Traffic Screenshots**

---

## 👩‍💻 Author
**Abosede Ogunlade**  
Cybersecurity Enthusiast & Analyst  

---

## 📄 View the Full Report

