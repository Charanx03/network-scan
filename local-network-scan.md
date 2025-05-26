#  Nmap Scan Summary

## Target IP Range:
192.168.145.0/24

## Scan Command Used:
nmap -sS 192.168.145.0/24

## Scan Type:
TCP SYN Scan (Stealth Scan)

---

## Results:

### Host: 192.168.145.231 (My Machine)
- 135/tcp open  (Microsoft RPC)
- 139/tcp open  (NetBIOS Session Service)
- 445/tcp open  (Microsoft Directory Services)

### Host: 192.168.145.45
- 53/tcp open   (DNS)

---

## Tools Used:
- Nmap v7.97

## Analysis:
- Common Windows ports are open on my own machine.
- DNS port (53) is open on the gateway 192.168.145.45.
- No unexpected open ports detected.

  ![Screenshot 2025-05-26 111109](https://github.com/user-attachments/assets/60a414b6-830f-4654-8998-35e6c2002bb8)




