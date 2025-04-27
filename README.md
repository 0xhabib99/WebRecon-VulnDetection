<h1 align="center">🔎 Web Application Reconnaissance and Vulnerability Detection 🔥</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Habibur%20Rahoman-blue" />
  <img src="https://img.shields.io/badge/Project-Type-Bash%20Automation-brightgreen" />
  <img src="https://img.shields.io/badge/Security-Focused-critical" />
</p>

---

## 📚 About the Project

This project is a **web application reconnaissance and vulnerability detection toolkit** built around a Bash script named `recon.sh`.

It automates key phases of penetration testing:
- Subdomain Enumeration
- Live Subdomain Detection
- URL Extraction (historical + live)
- Port Scanning
- Parameter Discovery
- Manual Vulnerability Testing (SQL Injection, XSS, Clickjacking)

It is designed to help **penetration testers**, **bug bounty hunters**, and **cybersecurity learners** quickly gather a **structured attack surface** and identify weak points for further manual analysis.

---

## 🛠️ Features

- 🔎 Subdomain Enumeration with Subfinder, Assetfinder, crt.sh
- 🌐 Live Host Detection with HTTPx
- 🗂️ URL Extraction with GAU and Waybackurls
- 🛰️ Port Scanning with Nmap
- 🎯 Parameter Discovery using ParamSpider
- 🧪 Manual Vulnerability Testing for:
  - SQL Injection (SQLi)
  - Cross-Site Scripting (XSS)
  - Clickjacking
  - Information Disclosure
- 📁 Organized outputs into structured folders for every target
- 🔧 Easily extensible with new tools and modules

---

## 🛠️ Tools Used

| Tool            | Purpose                            |
|-----------------|------------------------------------|
| Subfinder       | Subdomain Enumeration              |
| Assetfinder     | Subdomain Enumeration              |
| crt.sh          | Passive Subdomain Discovery        |
| HTTPx           | Alive Subdomain Checking           |
| GAU             | URL Extraction from various sources|
| Waybackurls     | URL History Extraction             |
| Nmap            | Port Scanning and Service Detection|
| ParamSpider     | URL Parameter Discovery            |

---
## Installation, Setup & Run

```bash
git clone https://github.com/0xhabib99/WebRecon-VulnDetection.git
cd WebRecon-VulnDetection
chmod +x Recon.sh  # Make the script executable
./recon.sh #to run




