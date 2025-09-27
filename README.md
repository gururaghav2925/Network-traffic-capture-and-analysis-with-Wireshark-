# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.



### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage
## 1. Open Wireshark and Select a Network Interface
• Launch Wireshark.
• Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2f2e12c9-1a01-4ae9-a0ce-f475ceb5050a" />



## 2. Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1bc8ea3e-ed77-48bf-9fc4-f36e51da6d86" />



## 3. Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter
bar to narrow down results.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2295d230-fcd4-48e9-8905-be7f18958166" />



## 4. Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,
IP, TCP/UDP layers, and data payload.


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b82b418f-937a-4158-ae35-a681cb12293f" />


## 5. Export or Save the Capture
• Go to File > Save As to store the capture in .pcap format for future analysis.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb97ba4b-f39a-402f-8a59-de040dbfab99" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3568a38e-ecd2-484a-975c-64d2810fd655" />



## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
