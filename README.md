# Text Encryption Tool (文本加密工具)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-purple)](https://kotlinlang.org/)
[![API](https://img.shields.io/badge/API-21%2B-brightgreen)](https://developer.android.com/)

**English** | [中文](#中文版)

---

## English

### Overview

A lightweight Android app for symmetric encryption/decryption of text using **AES-256-GCM** (Galois/Counter Mode). It supports custom passphrase‑based key derivation, random key generation, and outputs ciphertext in **Base64** or **Hex** format. Real‑time statistics, clipboard integration, and a long‑press context menu make it easy to use.

### Features

- 🔐 **AES‑256‑GCM encryption** with authenticated encryption (integrity & confidentiality).
- 🔑 **Passphrase‑to‑key** via SHA‑256 (or use a generated random key).
- 🎲 **One‑click random key generation** (32‑byte, Base64‑encoded).
- 📋 **Automatic copy to clipboard** after encryption/decryption/key generation.
- 📊 **Real‑time statistics**:
  - Plain text: UTF‑8 byte count.
  - Cipher text: length in Base64 characters or bytes (Hex mode).
- 🔄 **Output format switch** between Base64 and Hex.
- 🖱️ **Long‑press context menu** on each input field: Copy, Paste, Cut, Select All, Clear, plus `Encrypt current`/`Decrypt current`/`Generate key` shortcuts.
- 🛡️ **Error‑aware decryption** – shows friendly messages for wrong keys or corrupted data.

### Getting Started

#### Prerequisites
- Android Studio (latest stable)
- JDK 11+
- Android SDK (API 21+)

#### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/BI3BJU/Text-Encryption-Tool-Java.git
