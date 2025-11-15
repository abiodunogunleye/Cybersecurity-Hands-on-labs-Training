---
layout: single
title: "Episode 28: Wireshark Packet Analysis"
collection: labs
---

## Objective
Learn to capture, filter, and analyze network traffic using Wireshark.

## Tasks Completed
• Captured packets on active interfaces.  
• Applied filters like http, dns, tcp.port==80.  
• Inspected protocol headers for details.  
• Followed TCP streams.  
• Exported packet captures for reporting.

## Example Filters Used
http  
dns  
icmp  
tcp.port==443  
ip.addr==192.168.1.10

## Key Takeaways
• Wireshark gives full visibility into packet details.  
• Filters help isolate suspicious traffic.  
• Following streams supports clear investigation.  
• Packet inspection helps detect malicious patterns.

## SOC Application
SOC analysts review PCAP files during incidents.  
They validate network alerts and check protocol behavior.  
They use Wireshark for threat detection and forensic review.

## Next Step
Continue with Episode 29 on tcpreplay.
