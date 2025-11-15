---
layout: single
title: "Episode 24: SSH Remote Access"
collection: labs
---

## Objective
Learn to manage secure remote access using SSH. This supports system checks and investigations in SOC environments.

## Commands Practiced
ssh user@ip  
ssh -i key.pem user@ip  
ssh-copy-id user@ip  
systemctl status ssh  
who  
last  
ss -tulnp | grep ssh

## Key Takeaways
• SSH provides secure remote access.  
• Key-based authentication improves security.  
• SSH logs help track user activity.  
• SSH configuration impacts system hardening.

## SOC Application
SOC analysts check SSH logs for unauthorized access.  
They confirm active sessions and validate user activity.  
They monitor configuration changes that affect security.

## Next Step
Move to Episode 25 on scripting.
