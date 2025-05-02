# Network-traffic-capture-and-analysis-with-Wireshark
# Name: Reshma C
# Reg No: 212223040168
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
![image](https://github.com/user-attachments/assets/5fd4fca4-738d-49f0-9095-c8a0828e996f)
Start Capturing Packets

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.
![image](https://github.com/user-attachments/assets/db61d36b-81fa-45b3-a138-535d152ba96e)

Apply Filters to Focus on Specific Traffic

• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.
![image](https://github.com/user-attachments/assets/abe9994a-1bd3-4221-9d73-63b3ecbb71fd)

Analyze Packet Details

• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.
![image](https://github.com/user-attachments/assets/9f1e6fc0-4dd6-43ee-9cd6-00c54221a216)


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
