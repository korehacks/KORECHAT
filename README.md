# KØRE-CHAT
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-blue.svg)](https://www.kali.org)
[![Language](https://img.shields.io/badge/Language-Python%203-blue.svg)](https://python.org)

<p align="center">
  <img src="http://kore.unaux.com/logo.png" alt="KØRE Systems Logo" width="200">
</p>

**KØRE-CHAT** is a native, peer-to-peer encrypted messaging and file transfer utility designed exclusively for the **KØRE Systems** digital hub. Built with a focus on high-level security, it utilizes system-native OpenSSL/TLS to establish secure tunnels for communication and data exchange without relying on third-party servers.

---

## 🚀 Key Features
*   **Native TLS Encryption:** Leverages OpenSSL directly for secure, authenticated tunnels.
*   **Zero-Dependency:** Written in pure Python 3 using only the standard library.
*   **Prompt-Based Transfer:** Secure file exchange with "Accept/Reject" prompts to prevent unauthorized pushes.
*   **Auto-Provisioning:** Automatically generates RSA-2048 bit certificates on startup.
*   **Identity System:** Custom display names for clear communication within the hub.

## 🛠️ Installation

### Kali Linux / Linux
```bash
sudo apt update
sudo apt install python3 openssl git
git clone https://github.com/korehacks/KORECHAT/
cd KORECHAT
chmod +x korechat.py
python3 korechat.py --help
