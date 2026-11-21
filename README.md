# 🔐 PDF Password Cracking Labs — Week 3 (Modules 1 & 2)

![Category](https://img.shields.io/badge/Category-Cybersecurity%20%26%20Ethical%20Hacking-blue)
![Topic](https://img.shields.io/badge/Topic-Password%20Cracking-red)
![Tools](https://img.shields.io/badge/Tools-John%20the%20Ripper%20%7C%20Johnny%20GUI%20%7C%20Networkwalks-purple)

## 📌 Overview

This repository documents two hands-on cybersecurity lab tasks focused on auditing password strength and recovering lost credentials from encrypted PDF documents (`My Locked PDF1.pdf`). Both labs demonstrate how password hashes are extracted from protected files and cracked using dictionary attacks:

* **Project Module 1:** Offline password recovery using **John the Ripper (JTR)** CLI and **Johnny GUI** on Windows.
* **Project Module 2:** Browser-based hash extraction and dictionary cracking using **Networkwalks Online Tools**.

---

## 📂 Recommended Repository Structure

```text
pdf-password-cracking-labs/
├── README.md
├── hashes/
│   └── hash1.txt          # Extracted $pdf$ hash string (for JTR/Johnny)
└── screenshots/           # Lab verification & flag capture screenshots
