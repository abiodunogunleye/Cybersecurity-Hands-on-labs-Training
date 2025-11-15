---
layout: single
title: "Episode 23: netstat Command"
collection: labs
---

## Objective
Learn how to view network connections and listening services using netstat. These skills support network checks during investigations.

## Commands Practiced
netstat -ant  
netstat -tulnp  
netstat -an | grep ESTABLISHED  
netstat -an | grep LISTEN  
ss -tulnp as an alternative

## Key Takeaways
• Netstat shows active connections.  
• It helps highlight unusual ports.  
• It supports quick checks on system communication.  
• It helps confirm if a service runs at the wrong time.

## SOC Application
SOC analysts use netstat to validate network alerts and check for suspicious ports.  
They also use it to confirm if a host talks to an unknown IP.

## Next Step
Move to Episode 24 on SSH.
