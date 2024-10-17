# Network Traffic Analysis with Wireshark

## Objective
[Brief Objective - Remove this afterwards]

Network traffic analysis is a crucial skill in cybersecurity. Wireshark is a popular network protocol analyzer used to capture and analyze network traffic. This tutorial will guide you through installing, capturing, and analyzing network traffic using Wireshark.

### Skills Learned

- **Packet Capture and Filtering**: Gained expertise in capturing live network traffic and applying precise filters to isolate specific protocols, IP addresses, and conversations for detailed analysis.
  
- **Protocol Analysis and Troubleshooting**: Developed the ability to dissect and interpret various network protocols (e.g., TCP, UDP, DNS, HTTP) to identify abnormal traffic patterns, performance issues, and security threats.
  
- **Traffic Pattern Recognition**: Learned to use Wireshark’s statistical tools and I/O graphs to detect traffic anomalies, identify potential malicious activity, and troubleshoot network performance bottlenecks.

### Tools Used

-Packet Capture (PCAP)
-Display Filters
-Protocol Decoding
-Statistics Tools
-Expert Information
-Follow Streams

## Steps
Step 1: Install Wireshark

Sudo apt update

https://imgur.com/a/NIvJgjl

Sudo apt update file loading

https://imgur.com/a/uNuNsYG

Sudo apt install wireshark

https://imgur.com/a/DYpGMXs

Sudo apt install wireshark loading

https://imgur.com/a/QQCrIEM

Sudo apt install wireshark yes or no

https://imgur.com/a/nV02vUp

Sudo apt install wireshark yes or no configuring

https://imgur.com/a/3dF2ilt

Sudo usermod -aG wireshark $vboxuser

https://imgur.com/a/EdwegDL

Sudo usermod -aG wireshark $vboxuser file loading

https://imgur.com/a/qpdrcQm

Step 2: Launch wireshark

https://imgur.com/a/xOLOPRm

Select Network Interface

https://imgur.com/a/KLlA3zm

Step 3: Capture Network Traffic

Start Capturing

https://imgur.com/a/0zpBioc

Generating Traffic

https://imgur.com/a/A3HL7BP

Stop Capturing

https://imgur.com/a/uOiZhuK

Step 4: Analyze Network Traffic


HTTP traffic:

https://imgur.com/a/TyzK6VL

TCP traffic:

https://imgur.com/a/PsUIpun

Packets from a specific IP:

https://imgur.com/a/nGP75Ti

Packets to a specific port:

https://imgur.com/a/JLDUxFG

Follow TCP/UDP Streams

TCP Streams

https://imgur.com/a/g4TEjNn

UDP Stream:

https://imgur.com/a/X9BK3i7

Inspect Packet Contents

https://imgur.com/a/WOgKILi

Step 5: Save and Export Capture

Export Specific Packets

https://imgur.com/a/HkQMyXD

Step 6: Advanced Analysis

Protocol Hierarchy:

https://imgur.com/a/VIXuocp

Conversations:

https://imgur.com/a/eiFte1L

Endpoints:

https://imgur.com/a/96zdL92

Step 7: Socument your analysis

# Wireshark Capture Summary

### 1. **Capture Date and Time**
   - **Start Date and Time**: [10.16.2024; 6:34 pm]
   - **End Date and Time**: [10.16.2024 ; 7:04 pm]

### 2. **Duration of Capture**
   - **Total Duration**: [45 minutes]

### 3. **Network Interface Used**
   eth0]
   - **IP Address of Interface**: [192.168.1.1]
   - **MAC Address of Interface**: [PCSystemtec_44:87:4a]

### 4. **Packet Capture Statistics**
   - **Total Packets Captured**: [6]
   - **Protocols Observed**: [http, tcp,ip.addr == 192.168.1.1, tcp.port == 80













