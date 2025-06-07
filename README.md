# FUTURE_CS_03
# 🔐 Wi-Fi Security Assessment 

**Author:** Suryaganthan R 
**Platform:** Kali Linux
**Tools Used:** Nmap, Netdiscover, Wireshark  
**Date:** 7 ,June 2025

---

## 📋 Objective

Conduct a Wi-Fi security assessment on a personal network by checking for:
- Weak passwords
- Open ports
- Unauthorized devices

---

## 🧪 Environment

| Component        | Details                           |
|------------------|-----------------------------------|
| **Network Type** | Router         |
| **Encryption**   | WPA2-PSK                          |
| **Interface**    | No external Wi-Fi adapter         |
| **Testing OS**   | Kali Linux (latest)               |

---

## 🛠️ Tools & Commands Used

- **Nmap**: Scan for devices and open ports
  ```bash
  nmap -sV 192.168.43.1
  nmap -sn 192.168.43.0/24
