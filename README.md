# Real-Time Network Packet Analysis & Hybrid Network Intrusion Detection System (IDS)

| **Title** | Real-Time Network Packet Analysis & Hybrid Network Intrusion Detection System (IDS) |
|------------|--------------------------------------------------------------------------------------|
| **Description** | Java-based Hybrid Intrusion Detection System (IDS) that captures live network traffic and detects threats using signature-based and anomaly-based detection techniques. |
| **Author** | Alekhya Panguluri |

---

# Introduction

This project demonstrates the design and implementation of a **Hybrid Network Intrusion Detection System (IDS)** developed in Java using **Pcap4J**. The system captures live network packets, analyses network traffic in real time, detects suspicious activities using both signature-based and anomaly-based detection methods, and generates security alerts for investigation.

The project was validated using industry-standard tools including **Nmap**, **Wireshark**, and **hping3** to simulate network attacks and verify detection accuracy.

---

# Skills Demonstrated

- Java Programming
- Network Packet Analysis
- Network Security
- Intrusion Detection Systems (IDS)
- Signature-Based Detection
- Anomaly-Based Detection
- Threat Detection
- TCP/IP Networking
- Packet Analysis
- Security Event Logging
- Technical Documentation

---

# Technologies Used

- Java
- Pcap4J
- Npcap / libpcap
- Wireshark
- Nmap
- hping3
- TCP/IP Protocol Suite
- CSV Logging

---

# Project Features

- Real-Time Packet Capture
- Signature-Based Threat Detection
- Anomaly-Based Threat Detection
- TCP NULL Scan Detection
- TCP XMAS Scan Detection
- Suspicious Port Detection
- Port Scan Detection
- SYN Flood Detection
- Security Alert Logging
- CSV Report Generation

---

# System Architecture

The Hybrid IDS follows a layered architecture for capturing, analysing, and monitoring network traffic.

**Workflow**

1. Capture live network packets.
2. Process captured packets.
3. Perform signature-based analysis.
4. Perform anomaly-based analysis.
5. Generate security alerts.
6. Store alerts in CSV format.
7. Validate captured traffic using Wireshark.

---

# Testing Results

The Hybrid Network Intrusion Detection System was successfully tested against multiple simulated attack scenarios to validate its detection capabilities.

### Test Scenarios

- Nmap Port Scan Detection
- Real-Time IDS Monitoring
- Alert Log Analysis
- Behaviour-Based Port Scan Detection
- SYN Flood Detection
- Packet Capture
- Wireshark Validation

The system successfully detected suspicious activities and generated alerts during each test scenario.

---

# Project Documentation

The complete technical report is available in the **docs** folder.

**Project Report**

```text
docs/IDS_Technical_Project_Report.pdf
```

---

# Repository Structure

```text
Java-hybrid-network-intrusion-detection-system
│
├── README.md
├── docs
│   ├── README.md
│   └── IDS_Technical_Project_Report.pdf
│
└── screenshots
    ├── README.md
    ├── System Architecture.jpeg
    ├── Real-Time IDS Console During Monitoring.jpeg
    ├── Nmap Port Scan Against the Target System.jpeg
    ├── Generated Security Alerts Stored in CSV Format.jpeg
    ├── Behaviour-Based Scan Detection.jpeg
    ├── Detection of Suspicious Port Connections.jpeg
    ├── SYN Flood Attack Detection.jpeg
    ├── Captured Network Traffic.jpeg
    └── Wireshark Validation of Captured Packets.jpeg
```

---

# Future Improvements

- Machine Learning-Based Threat Detection
- SIEM Integration (Wazuh / Splunk)
- Dashboard for Alert Visualisation
- Email Alert Notifications
- IPv6 Traffic Support
- Threat Intelligence Integration
- Cloud Deployment

---

# License

This project is intended for educational and portfolio purposes.
