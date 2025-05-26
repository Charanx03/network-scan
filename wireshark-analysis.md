#  Wireshark Packet Analysis (Port 80)
- Source IP: 192.168.145.231 (my machine)
- Destination IP: 192.168.145.45 (target)
- Port Scanned: TCP port 80

# 1. SYN Packet Sent:
   192.168.145.231 → 192.168.145.45: TCP 63304 → 80 [SYN]
# 2. Response:
   192.168.145.45 → 192.168.145.231: TCP 80 → 63304. [RST,ACK]

# Conclusion: 
Port 80 is closed on 192.168.145.45 (reset received).

![Screenshot 2025-05-26 194005](https://github.com/user-attachments/assets/14cc8945-e87a-4553-9d42-d57862b912ab)

