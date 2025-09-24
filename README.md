# network-scan-using-nmap
task 1
# 🔐 Cyber Security Internship – Task 1

## 🧠 Objective
Perform a network scan using Nmap to discover open ports on devices in your local network and understand potential security risks.

---

## 🛠 Tools Used
- **Nmap v7.98** (Free and open-source)
- No paid tools or Wireshark used

---

## 🌐 Network Configuration
- **Device IP**: 192.168.56.1  
- **Subnet Mask**: 255.255.255.0  
- **Scan Range**: 192.168.56.0/24

---

## 🚀 Scan Command Used
```bash
nmap -sS -Pn 192.168.56.0/24
1️⃣ scan_results.txt
Include your raw Nmap output. You can generate it using:
nmap -sS -Pn 192.168.56.0/24 -oN scan_results.txt

git add screenshots/
git commit -m "Added screenshots"
git push


