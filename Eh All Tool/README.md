<h1>🛡️ Eh All Tool — All-in-One Ethical Hacking Suite</h1>
  <p><strong>A modular, lightweight, and versatile penetration testing & security auditing toolkit.</strong></p>

  <!-- GitHub Badges -->
  <p>
    <a href="https://github.com/TheUniqueWeb/CyberSecurity-Tools/stargazers"><img src="https://img.shields.io/github/stars/TheUniqueWeb/CyberSecurity-Tools?style=for-the-badge&color=ffd700" alt="Stars"></a>
    <a href="https://github.com/TheUniqueWeb/CyberSecurity-Tools/network/members"><img src="https://img.shields.io/github/forks/TheUniqueWeb/CyberSecurity-Tools?style=for-the-badge&color=00c853" alt="Forks"></a>
    <a href="https://github.com/TheUniqueWeb/CyberSecurity-Tools/issues"><img src="https://img.shields.io/github/issues/TheUniqueWeb/CyberSecurity-Tools?style=for-the-badge&color=ff5722" alt="Issues"></a>
    <a href="https://github.com/TheUniqueWeb/CyberSecurity-Tools/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License"></a>
  </p>

  <!-- Technology Badges -->
  <p>
    <img src="https://img.shields.io/badge/Language-Python%20%7C%20Bash-yellowgreen?style=flat-square&logo=python" alt="Language">
    <img src="https://img.shields.io/badge/Platform-Kali%20%7C%20Parrot%20%7C%20Ubuntu%20%7C%20Termux-blue?style=flat-square&logo=linux" alt="OS Support">
    <img src="https://img.shields.io/badge/Status-Actively%20Maintained-success?style=flat-square" alt="Status">
    <img src="https://img.shields.io/badge/Author-TheUniqueWeb-informational?style=flat-square&logo=github" alt="Author">
  </p>

  <p align="center">
    <a href="#-about-the-project">About</a> •
    <a href="#-key-features--modules">Modules</a> •
    <a href="#-installation--setup">Installation</a> •
    <a href="#-usage--menu-preview">Usage</a> •
    <a href="#-educational--legal-disclaimer">Disclaimer</a> •
    <a href="#-credits--author">Credits</a>
  </p>
</div>

---

## 📖 About The Project

**Eh All Tool** হলো [TheUniqueWeb/CyberSecurity-Tools](https://github.com/TheUniqueWeb/CyberSecurity-Tools) রিপোজিটরির একটি বিশেষায়িত অল-ইন-ওয়ান ফ্রেমওয়ার্ক। এটি এথিক্যাল হ্যাকার, সিকিউরিটি এনালিস্ট এবং বাগ হান্টারদের প্রতিদিনের রিকননেসান্স, অ্যাসেসমেন্ট এবং টেস্টিং কাজগুলো দ্রুত ও স্বয়ংক্রিয়ভাবে সম্পন্ন করার সুবিধার্থে তৈরি করা হয়েছে। 

একাধিক আলাদা আলাদা কমান্ড রান করার ঝামেলা দূর করে একটি মাত্র ইন্টারফেস থেকে সমস্ত দরকারি টুলস চালানোই এই প্রজেক্টের প্রধান লক্ষ্য।

---

## ⚡ Key Features & Modules

<details open>
<summary><b>1. 🛰️ Information Gathering & Reconnaissance</b></summary>

* **WHOIS & Reverse IP Lookup:** টার্গেটের ডোমেইন হিস্ট্রি ও আইপি সংক্রান্ত ডাটা এক্সট্র্যাক্ট করে।
* **Subdomain Enumeration:** পাবলিক ব্রুটফোর্স এবং API ব্যবহার করে সাবডোমেইন খুঁজে বের করে।
* **Port Scanner:** মাল্টি-থ্রেডেড ফাস্ট পোর্ট এবং সার্ভিস ব্যানার গ্র্যাবার।
* **DNS Lookup:** MX, TXT, A, CNAME এবং NS রেকর্ড স্ক্যানিং।
</details>

<details>
<summary><b>2. 🌐 Web Application Security Testing</b></summary>

* **Admin Panel Finder:** সাধারণ এবং কাস্টম পাথ স্ক্যান করে লুকানো অ্যাডমিন লগইন পেজ ডিটেক্ট করে।
* **Vulnerability Checks:** SQLi, XSS, ও Open Redirect-এর প্রাথমিক ভালনারেবিলিটি টেস্ট।
* **CMS & Tech Stack Detector:** WordPress, Joomla, Drupal ও সার্ভার হেডারের তথ্য সনাক্তকরণ।
* **Endpoint & Directory Discovery:** ওয়েবসাইটের সংবেদনশীল ফাইল (`.env`, `config.php`, `.git`) ব্রুটফোর্স।
</details>

<details>
<summary><b>3. 📡 Network & Wireless Auditing</b></summary>

* **Host Discovery:** লোকাল নেটওয়ার্কে সক্রিয় হোস্ট ও আইপি অ্যাড্রেস লিস্ট করা।
* **ARP & Packet Helper:** ট্রাফিক এনালাইসিস ও আর্প প্যাকেট ইন্সপেকশন টুলস।
* **Wi-Fi Monitoring Support:** হ্যান্ডশেক ক্যাপচার ও নেটওয়ার্ক টেস্ট সহায়িকা।
</details>

<details>
<summary><b>4. 🕵️ OSINT & Digital Footprinting</b></summary>

* **Username & Email Search:** সোশ্যাল মিডিয়া এবং বিভিন্ন পাবলিক ডাটাবেসে ইউজারনেম ট্র্যাক করা।
* **Exif Metadata Extractor:** ছবির ভেতরের মেটাডাটা ও জিপিএস লোকেশন বের করা।
* **Phone Number OSINT:** ক্যারিয়ার, লোকেশন ও কান্ট্রি কোড অ্যানালাইসিস।
</details>

<details>
<summary><b>5. 🔐 Cryptography, Hashes & Utilities</b></summary>

* **Hash Identifier:** MD5, SHA-1, SHA-256, NTLM ইত্যাদি হ্যাশের ধরন শনাক্তকরণ।
* **Decoder / Encoder:** Base64, Hex, URL, Binary কনভার্টার।
</details>

---

## 💻 System Requirements

টুলটি সঠিকভাবে রান করার জন্য আপনার সিস্টেমে নিচের পরিবেশগুলো নিশ্চিত করুন:

* **অপারেটিং সিস্টেম:** Kali Linux / Parrot Security OS / Ubuntu / Debian / Termux (Android)
* **Python ভার্সন:** `Python 3.8+`
* **টুলস ও ডিপেনডেন্সি:** `git`, `curl`, `wget`, `bash`

---

## 📥 Installation & Setup

টার্মিনালে সরাসরি নিচের কমান্ডগুলো একের পর এক এক্সিকিউট করুন:

```bash
# ১. রিপোজিটরি ক্লোন করুন
git clone https://github.com/TheUniqueWeb/CyberSecurity-Tools.git

# ২. Eh All Tool ফোল্ডারে প্রবেশ করুন
cd CyberSecurity-Tools/"Eh All Tool"

# ৩. প্রয়োজনীয় ফাইলের এক্সিকিউশন পারমিশন দিন
chmod +x *

# ৪. ডিপেনডেন্সি বা রিকয়ারমেন্টস ইন্সটল করুন
pip install -r requirements.txt
# অথবা সেটআপ স্ক্রিপ্ট থাকলে:
# bash setup.sh
