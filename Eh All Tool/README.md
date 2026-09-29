<div align="center">

  <h1>🛡️ CyberSecurity-Tools (EH All Tools)</h1>
  <p><strong>A Comprehensive Multi-Tool Suite for Ethical Hackers, Pentesters & Security Researchers</strong></p>

  <!-- Badges -->
  <p>
    <a href="https://github.com/TheUnqiueWeb/CyberSecurity-Tools/graphs/contributors"><img src="https://img.shields.io/github/contributors/TheUnqiueWeb/CyberSecurity-Tools?color=brightgreen&style=for-the-badge" alt="Contributors"></a>
    <a href="https://github.com/TheUnqiueWeb/CyberSecurity-Tools/network/members"><img src="https://img.shields.io/github/forks/TheUnqiueWeb/CyberSecurity-Tools?style=for-the-badge" alt="Forks"></a>
    <a href="https://github.com/TheUnqiueWeb/CyberSecurity-Tools/stargazers"><img src="https://img.shields.io/github/stars/TheUnqiueWeb/CyberSecurity-Tools?style=for-the-badge" alt="Stars"></a>
    <a href="https://github.com/TheUnqiueWeb/CyberSecurity-Tools/issues"><img src="https://img.shields.io/github/issues/TheUnqiueWeb/CyberSecurity-Tools?style=for-the-badge" alt="Issues"></a>
    <a href="https://github.com/TheUnqiueWeb/CyberSecurity-Tools/blob/main/LICENSE"><img src="https://img.shields.io/github/license/TheUnqiueWeb/CyberSecurity-Tools?style=for-the-badge" alt="License"></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square" alt="Maintenance">
    <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Termux-blue.svg?style=flat-square" alt="Platform">
    <img src="https://img.shields.io/badge/Python-3.8%2B-yellow.svg?style=flat-square" alt="Python">
  </p>

  <p align="center">
    <a href="#-about-the-project">About</a> •
    <a href="#-features--tool-categories">Features</a> •
    <a href="#-installation--setup">Installation</a> •
    <a href="#-usage">Usage</a> •
    <a href="#-disclaimer">Disclaimer</a> •
    <a href="#-credits--author">Credits</a>
  </p>
</div>

---

## 📌 About The Project

**CyberSecurity-Tools** হলো একটি অল-ইন-ওয়ান ফ্রেমওয়ার্ক যা সাইবার সিকিউরিটি রিসার্চার, এথিক্যাল হ্যাকার এবং বাগ বাউন্টি হান্টারদের জন্য বিশেষভাবে ডিজাইন করা হয়েছে। রিকন থেকে শুরু করে এক্সপ্লয়েটেশন—সব ধরণের প্রাথমিক ও অ্যাডভান্সড টুলসকে এক জায়গায় ইন্টিগ্রেট করে সময় বাঁচানোই এই প্রজেক্টের মূল উদ্দেশ্য।

> ⚡ **Developed with ❤️ by [TheUnqiueWeb](https://github.com/TheUnqiueWeb)**

---

## 🚀 Features & Tool Categories

এই সুইটে বিভিন্ন ক্যাটাগরির প্রয়োজনীয় টুলসগুলো সাজানো রয়েছে:

### 1. 🔍 Reconnaissance & Information Gathering
* Subdomain Finder & DNS Enumerator
* IP / WHOIS Lookup & Reverse IP Scanner
* Port Scanner (TCP/UDP multi-threaded)
* CMS Detection (WordPress, Joomla, Drupal, etc.)

### 2. 🌐 Web Application Security
* SQL Injection (SQLi) Detection Helper
* Cross-Site Scripting (XSS) Scanner
* Admin Panel & Sensitive File Finder
* Directory & Endpoint Bruteforcer

### 3. 📡 Network & Wireless Security
* Network Host Discovery
* ARP Spoofer & Packet Sniffer helper
* Wi-Fi Monitor & Handshake Capture utilities

### 4. 🕵️ OSINT (Open Source Intelligence)
* Social Media Profile Extractor
* Email & Username Scraping
* Metadata Extractor (ExifTool Integration)

### 5. 🔐 Cryptography & Encoding
* Hash Cracking / Identifying Utility (MD5, SHA-256, etc.)
* Base64 / Hex / URL Encoder & Decoder

---

## 💻 System Requirements

* **OS:** Kali Linux, Parrot Security OS, Ubuntu, Debian, macOS, or Termux (Android)
* **Python:** Version `3.8+`
* **Dependencies:** `git`, `curl`, `pip`, `bash`

---

## 📥 Installation & Setup

খুব সহজেই কমান্ড লাইনে নিচের স্টেপগুলো ফলো করে ইন্সটল করতে পারেন:

```bash
# ১. রিপোজিটরি ক্লোন করুন
git clone https://github.com/TheUnqiueWeb/CyberSecurity-Tools.git

# ২. প্রজেক্ট ডিরেক্টরিতে যান
cd CyberSecurity-Tools

# ৩. পারমিশন দিন
chmod +x setup.sh install.sh main.py

# ৪. ডিপেনডেন্সি ইন্সটল করুন
bash setup.sh
# অথবা
pip install -r requirements.txt
