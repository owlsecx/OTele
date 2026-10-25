# 🦉 OTele

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OTele** — Authorized physical-security motion monitor with optional Telegram alerts (lab/local defaults)

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OTele is an authorized motion-monitoring tool that watches a camera feed for movement and can send alerts to a configured destination. It captures frames via OpenCV, detects motion against a rolling baseline, and records clips for review. It is intended strictly for authorized physical-security and lab use.

---

## ✨ Features


- Camera-based motion detection using OpenCV frame differencing
- Configurable capture interval, clip duration and camera index
- Alerting to a configured endpoint (token/chat id stored in a local config file)
- Rolling-baseline detection to reduce false triggers
- Local JSON configuration persisted to the user's home directory
- Desktop UI in the OWLSec theme with an offline --self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OTele
./OTele --self-test
./OTele --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
