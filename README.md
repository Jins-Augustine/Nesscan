# Nesscan
🔍 Performed a local vulnerability scan using Nessus Essentials to identify, document, and understand security risks on the system.



# 🔍 Nessus Vulnerability Scan - Localhost

This project documents a full vulnerability scan performed on a local machine using **Nessus Essentials**.

## 🧪 Tools Used
- Kali Linux
- Nessus Essentials (Free)
- Firefox (localhost:8834 for interface)

## 🔧 Steps Performed

1. Installed Nessus Essentials on Kali Linux
2. Activated via email with the free activation code
3. Set target as `127.0.0.1` (localhost)
4. Ran a **Basic Network Scan** 
5. Waited for scan completion (approx 30–60 min)
6. Reviewed and documented vulnerabilities
7. Captured remediation suggestions

## 📁 Folder Structure

- [SCREENSHOTS](screenshots/): All screenshots
- [REPORT](report.md): Detailed findings
- `README.md`: This file

## 📄 Report Highlights

- Total vulnerabilities found: **74**
- Critical: 1
- High: Several Node.js, SSL, Python Tornado issues
- Remediations suggested: Upgrade Node.js, OpenSSH, and Tornado

---

📌 This is for educational/lab purposes only.
