# 💊 PharmaCare PRO — Interactive Pharmacy Management & AI Vision OCR

<div align="center">

[![Author](https://img.shields.io/badge/Author-0dh4m-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/0dh4m)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-PharmaCare%20PRO-0284c7?style=flat-square&logo=google-chrome&logoColor=white)](https://0dh4m.github.io/portfolio/demos/pharmacare/index.html)
[![AI Engine](https://img.shields.io/badge/AI%20Vision-Gemini%201.5%20OCR-38bdf8?style=flat-square)](https://github.com/0dh4m/pharmacare-pro-ai)
[![License](https://img.shields.io/badge/License-MIT-slate?style=flat-square)](LICENSE)

</div>

**PharmaCare PRO** is an interactive pharmacy management demo built around a modern dispensary workflow. It combines multimodal optical prescription recognition (Gemini Vision OCR), drug-drug interaction warning checks, synthesized audio barcode scanning, and multi-currency Moroccan Dirham (MAD) inventory telemetry.

> **Scope:** this repository contains the browser-side interactive demo (single-page app with LocalStorage persistence). The production PHP/MySQL backend is not included.

---

## ⚡ Core Engineering Highlights

- **Multimodal AI Prescription Scanner**: Optical scanning and text extraction from handwritten medical prescriptions using Google Gemini Vision, parsing drug names, dosages, and administration frequencies.
- **Drug-Drug Contraindication Matrix**: Automated cross-examination against patient medical history to prevent adverse drug interactions in real time.
- **Web Audio Barcode Feedback**: Synthesized low-latency audio frequency beeps (`AudioContext` oscillator) on POS barcode scanning.
- **Moroccan Dirham (MAD) Financial Analytics**: Interactive Chart.js dashboard tracking daily sales, margins, inventory alerts, and printable tax receipts.

---

## 🚀 Live Demo

Experience the live interactive application directly in the browser:
👉 **[Launch PharmaCare PRO Live Demo](https://0dh4m.github.io/portfolio/demos/pharmacare/index.html)**

---

## 🛠️ Tech Stack

- **Frontend & UI**: HTML5, Modern Vanilla JavaScript (ES6+), Tailwind CSS, Bootstrap Icons, Chart.js
- **Audio Subsystem**: Web Audio API (Synthesized POS barcode scanner)
- **AI Integration**: Google Gemini 1.5 Multimodal Optical Character Recognition (OCR)
- **State Management**: LocalStorage persistent cache with an in-browser transaction simulation

---

## 👨‍💻 Author

**Adham Cherkaoui Eddeqaqi (`0dh4m`)**
- 📍 Rabat / Salé, Morocco
- ✉️ `0dh4mm@gmail.com`
- 🌐 [0dh4m.github.io](https://0dh4m.github.io/)

---

## 📄 License

MIT — see [LICENSE](LICENSE).
