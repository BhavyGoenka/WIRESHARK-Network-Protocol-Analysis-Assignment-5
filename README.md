# WIRESHARK-Network-Protocol-Analysis-Assignment-5
This project focuses on analyzing network traffic using Wireshark. It involves capturing live packets, identifying multiple protocols such as HTTP, TCP, and DNS, applying filters, and exporting data as .pcap files. The task helps understand protocol behavior and basic network analysis techniques.
Task: Network Traffic Capture and Analysis using Wireshark  

## Objective  
To learn how to capture, filter, and analyze network traffic using Wireshark, and to identify different protocols involved in communication.  

## Tools Used  
- Wireshark (latest version)  
- Active network interface (Wi-Fi / Ethernet)  

## Step 1: Installation  
- Installed Wireshark from the official website.  
- Launched the tool and verified that the network interfaces were available.  

## Step 2: Capturing Packets  
- Started packet capture on the active network interface.  
- Generated traffic by browsing a website and running a ping command to an external server.  
- Captured traffic for about 1 minute before stopping the capture.  

## Step 3: Filtering Packets  
Applied filters to view specific protocols:  
- *DNS* – Observed domain name resolution queries and responses.  
- *HTTP* – Captured basic web browsing traffic.  
- *TCP* – Analyzed packet flow for connection establishment and data transfer.  

## Step 4: Identified Protocols  
At least 3 protocols identified from the capture:  
- *DNS:* Used to translate domain names into IP addresses.  
- *TCP:* Transport protocol ensuring reliable delivery of data.  
- *HTTP:* Application layer protocol for web traffic.  

## Step 5: Exporting Data  
- Saved the packet capture as a .pcap file for documentation.  
- Screenshots of filtered protocols were also taken for evidence.  
## Step 6: Findings & Observations  
- *DNS Packets:* Showed queries and responses for the visited websites.  
- *TCP Packets:* Displayed the three-way handshake process (SYN, SYN-ACK, ACK).  
- *HTTP Packets:* Contained web traffic details such as GET requests and responses.  
- Capturing live traffic revealed how multiple protocols work together for even simple actions like browsing a website or pinging a server.  

## Screenshots  
Screenshots of the packet captures and protocol filters are included in the /screenshots folder.  

## Conclusion  
This task demonstrated how to:  
- Capture live network traffic using Wireshark.  
- Filter traffic by protocol to focus on relevant packets.  
- Understand the roles of different network protocols in communication.  
- Export and document packet captures for further analysis.  

 *Outcome:* I successfully used Wireshark to capture, filter, and analyze packets, identified at least 3 protocols, and documented the findings with screenshots.
