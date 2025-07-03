# 🛡️ Enterprise mDNS Threat Detection with Wireshark & Splunk

This project simulates the detection of suspicious network behavior — specifically reverse DNS lookups via mDNS and potential HTTPS tunnel traffic — using packet capture and Splunk. The goal is to showcase real-world threat hunting and detection engineering using common tools.

---

## 📌 Project Objectives

- Capture real mDNS and encrypted traffic
- Identify abnormal PTR (reverse DNS) queries to external IPs
- Detect encrypted outbound connections using TLS over port 443
- Build and test SPL (Splunk Processing Language) detection queries
- Document the findings in a structured and beginner-friendly format

---

## 🧰 Tools Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Wireshark   | Capture and inspect network traffic (PCAP) |
| Splunk      | Analyze traffic and create detection logic |
| tshark      | Convert PCAP to readable format (optional) |
| GitHub      | Document and share the project    |

---

## 📁 Project Structure

