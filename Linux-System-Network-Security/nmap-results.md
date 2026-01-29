# Network Scanning

## 🔎 Tool Used
Nmap

## 🧪 Command Used
nmap -sC -sV -oN nmap-scan.txt <TARGET-IP>

## 📌 Findings
- Multiple open TCP ports detected
- Services running with outdated versions
- Unnecessary services exposed to the network

## 🧠 Security Impact
Open and outdated services increase the attack surface and may allow attackers to exploit known vulnerabilities.

## ✅ Recommendation
- Close unused ports
- Update running services
- Apply firewall rules
