# Linux Privilege Escalation Analysis

## 🔧 Tool Used
LinPEAS

## 🔍 Checks Performed
- SUID binaries
- File permissions
- Cron jobs
- Kernel version

## 📌 Findings
- Misconfigured file permissions
- SUID binaries present

## 🧠 Security Impact
Misconfigurations can allow attackers to escalate privileges and gain full system access.

## ✅ Recommendation
- Remove unnecessary SUID permissions
- Apply least privilege principle
- Regular system audits
