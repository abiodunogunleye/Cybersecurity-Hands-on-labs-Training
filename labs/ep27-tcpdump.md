---
layout: single
title: "Episode 27: tcpdump Packet Capture"
collection: labs
---

## Objective
Learn how to capture and analyze network packets using tcpdump. This supports network analysis during incidents.

## Commands Practiced
tcpdump  
tcpdump -i eth0  
tcpdump -n  
tcpdump -nn port 80  
tcpdump -w capture.pcap  
tcpdump -r capture.pcap  
tcpdump host 192.168.1.10  
tcpdump udp  
tcpdump icmp

## Key Takeaways
• Tcpdump captures live packets on an interface.  
• Filters help narrow down specific traffic.  
• Captures can be saved for later review.  
• Packet headers help identify suspicious behavior.

## SOC Application
SOC analysts use tcpdump to check network alerts.  
They confirm if suspicious traffic exists.  
They investigate anomalies that require packet-level detail.

## Next Step
Move to Episode 28 on Wireshark.
