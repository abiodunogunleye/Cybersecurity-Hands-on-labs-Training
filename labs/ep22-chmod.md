---
layout: single
title: "Episode 22: chmod Command"
collection: labs
---

## Objective
Learn to manage file and directory permissions using the `chmod` command, essential for securing Linux systems in SOC environments.

---

## Commands Practiced
| Command | Description |
|----------|-------------|
| `chmod 644 file.txt` | Owner read-write, others read-only |
| `chmod 600 key.pem` | Owner-only access |
| `chmod +x script.sh` | Add execute permission |
| `chmod -R 755 /var/www` | Recursive permission changes |
| `ls -l` | View file permissions |

---

## Key Takeaways
- Permissions protect sensitive files and logs.
- chmod supports octal and symbolic modes.
- Misconfigured permissions are a common attack vector.
- Knowing permission states helps analysts spot privilege issues.

---

## SOC Application
SOC analysts use chmod when:
- Securing log files
- Restricting access to scripts
- Hardening monitored systems
- Detecting unauthorized permission changes

---

## Next Step
Continue the lab series with Episode 23.
