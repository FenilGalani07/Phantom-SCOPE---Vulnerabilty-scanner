# PHANTOM SCOPE – Vulnerability Scanner
**Exploit + Precision = Complete Vulnerability Detection**

**PHANTOM SCOPE** is a next-gen Nmap-based vulnerability scanner designed for cybersecurity researchers, bug bounty hunters, and penetration testers. Built entirely in Bash, it provides an intuitive terminal UI and 25+ scanning techniques—ranging from basic reconnaissance to complex firewall evasion and vulnerability exploitation.

![PHANTOM SCOPE](https://img.shields.io/badge/Bash-Script-blue?logo=gnu-bash&style=for-the-badge)

---

## 🚀 Preview

### Initialization Banner
<img width="857" height="513" alt="intro" src="https://github.com/user-attachments/assets/e9360ed2-20b6-47ed-b813-f2e2ed27349f" />

### Main Menu
<img width="678" height="339" alt="Tasks" src="https://github.com/user-attachments/assets/7c77eec8-d63d-4e22-b197-e12db4d27b99" />

### Sample Output 1
<img width="845" height="444" alt="Output1" src="https://github.com/user-attachments/assets/38cc5979-9b64-4cdf-9d7e-c26314d7bf3f" />

### Sample Output 2
<img width="993" height="927" alt="Output2" src="https://github.com/user-attachments/assets/d2b0826e-c7d0-4922-b774-c562c37e463a" />

---

## 🔍 Features

- ✅ Interactive terminal interface with animated headers
- ✅ Auto-installs required dependencies (e.g. `nmap`, `figlet`)
- ✅ Includes 25+ scanning techniques:
  - TCP SYN, UDP, Ping, OS & version detection
  - Aggressive scans, top/all port scans
  - Nmap NSE vulnerability scripts
  - DNS brute-force, HTTP/FTP/SMB enumeration
  - Whois lookups, WAF detection, MAC spoofing
  - Firewall evasion techniques
  - Exportable output in multiple formats
- ✅ Safe execution prompts and cleanup logic
- ✅ Perfect for both beginners and advanced testers

---

## 📦 Requirements

- `nmap`
- `figlet` (for banner display)
- Linux OS (tested on Kali Linux & Ubuntu)

---

## 🔧 Installation

```bash
# Clone this repository
git clone https://github.com/FenilGalani07/Phantom-SCOPE---Vulnerabilty-scanner.git

# Navigate into the directory
cd Phantom-SCOPE---Vulnerabilty-scanner

# Make the script executable
chmod +x PhantomScope.sh

# Run the tool
./PhantomScope.sh
