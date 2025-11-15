---
layout: single
title: "Episode 26: curl Command"
collection: labs
---

## Objective
Learn how to transfer data, test endpoints, and inspect web responses using curl.

## Commands Practiced
curl http://example.com  
curl -O http://example.com/file.txt  
curl -I http://example.com  
curl -X POST -d "name=test" http://example.com  
curl -v http://example.com

## Key Takeaways
• Curl retrieves and posts data to remote servers.  
• It helps check response codes and headers.  
• It supports file downloads for investigation.  
• Verbose mode gives useful troubleshooting details.

## SOC Application
SOC analysts use curl to test URLs.  
They confirm server responses during incidents.  
They check if suspicious domains trigger downloads.

## Next Step
Move to Episode 27 on tcpdump.
