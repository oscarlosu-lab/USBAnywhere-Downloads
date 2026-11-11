# USBAnywhere — Official Distribution & Mirror Archive

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Project-FF5E5B?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/oscarlosu)
[![License](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)

This repository serves as the centralized backup mirror and distribution archive for releases across the USBAnywhere open-source ecosystem.

Official releases, source code, issue trackers, and technical discussions are hosted in their respective primary repositories:

- **Windows & Linux Client**: [oscarlosu-lab/USBAnywhere](https://github.com/oscarlosu-lab/USBAnywhere)
- **Windows, macOS & Linux Server**: [oscarlosu-lab/USBAnywhere-Server](https://github.com/oscarlosu-lab/USBAnywhere-Server)
- **Android & Android TV**: [oscarlosu-lab/USBAnywhere-Android](https://github.com/oscarlosu-lab/USBAnywhere-Android)
- **Web Portal & Documentation**: [oscarlosu-lab.github.io/USBAnywhere](https://oscarlosu-lab.github.io/USBAnywhere/)
- **Community Forum**: [r/UsbAnywhere](https://www.reddit.com/r/UsbAnywhere/)

---

## Current Stable Releases (v3.3.1)

### 1. USBAnywhere Client (Windows 10 / 11 & Linux)

**Version 3.3.1** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere/releases/tag/v3.3.1) | [Mirror Release](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/tag/client-v3.3.1)

| Package | Architecture / OS | Format | Download Link |
|---|---|---|---|
| Windows Installer | Windows 10/11 x64 | Setup EXE | [USBAnywhere_Setup_v3.3.1.exe](https://github.com/oscarlosu-lab/USBAnywhere/releases/download/v3.3.1/USBAnywhere_Setup_v3.3.1.exe) |
| Portable Archive | Windows 10/11 x64 | ZIP | [USBAnywhere-v3.3.1-x64.zip](https://github.com/oscarlosu-lab/USBAnywhere/releases/download/v3.3.1/USBAnywhere-v3.3.1-x64.zip) |
| Portable Archive | Windows 10/11 ARM64 | ZIP | [USBAnywhere-v3.3.1-arm64.zip](https://github.com/oscarlosu-lab/USBAnywhere/releases/download/v3.3.1/USBAnywhere-v3.3.1-arm64.zip) |
| Universal Linux Client & Server | Linux (`vhci_hcd` + `TCP 3241`) | TAR.GZ | [USBAnywhere-Linux-v3.3.1.tar.gz](https://github.com/oscarlosu-lab/USBAnywhere/releases/download/v3.3.1/USBAnywhere-Linux-v3.3.1.tar.gz) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere/releases/download/v3.3.1/SHA256SUMS.txt) |

---

### 2. USBAnywhere Server (Windows 10 / 11)

**Version 3.3.1** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/tag/v3.3.1) | [Mirror Release](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/tag/server-v3.3.1)

| Package | Architecture | Format | Download Link |
|---|---|---|---|
| Windows Installer | x64 | Setup EXE | [USBAnywhere-Server_Setup_v3.3.1.exe](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/USBAnywhere-Server_Setup_v3.3.1.exe) |
| Portable Archive | x64 | ZIP | [USBAnywhere-Server-v3.3.1-x64-Portable.zip](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/USBAnywhere-Server-v3.3.1-x64-Portable.zip) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/SHA256SUMS.txt) |

---

### 3. USBAnywhere Android & Android TV

**Version 3.3.0** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere-Android/releases/tag/v3.3.0)

| Package | Platform | Format | Download Link |
|---|---|---|---|
| Standalone Sideload Package | Android 8.0+ / Android TV / Shield | APK | [USBAnywhere-Android-v3.3.0.apk](https://github.com/oscarlosu-lab/USBAnywhere-Android/releases/download/v3.3.0/USBAnywhere-Android-v3.3.0.apk) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Android/releases/download/v3.3.0/SHA256SUMS.txt) |

---

### 4. USBAnywhere Server for macOS (Apple Silicon M1..M4 & Intel)

**Version 3.3.1** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/tag/v3.3.1) | [Documentation Guide](https://github.com/oscarlosu-lab/USBAnywhere-Server/blob/main/docs/USAGE_MACOS_EN.md)

| Package | Platform | Format | Download / Installation |
|---|---|---|---|
| 1-Click Automated Setup | macOS 13+ (Ventura, Sonoma, Sequoia) | Shell Script | `curl -fsSL https://raw.githubusercontent.com/oscarlosu-lab/USBAnywhere-Server/main/scripts/install-server-mac.sh \| sudo bash` |
| Native Universal Binary | macOS 13+ (Apple Silicon & Intel) | Binary | [usbanywhere-server-mac](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/usbanywhere-server-mac) |
| Release Tarball Bundle | macOS 13+ (Universal) | TAR.GZ | [USBAnywhere-Server-macOS-v3.3.1.tar.gz](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/USBAnywhere-Server-macOS-v3.3.1.tar.gz) |
| Release ZIP Archive | macOS 13+ (Universal) | ZIP | [USBAnywhere-Server-macOS-v3.3.1.zip](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/USBAnywhere-Server-macOS-v3.3.1.zip) |
| SHA-256 Checksums | macOS | TXT | [SHA256SUMS-macOS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/download/v3.3.1/SHA256SUMS-macOS.txt) |

---

## Verifying Integrity

To verify the integrity of any downloaded package against its published SHA-256 checksum:

### Windows (PowerShell)
```powershell
Get-FileHash .\USBAnywhere_Setup_v3.3.1.exe -Algorithm SHA256
```

### Linux / macOS
```bash
sha256sum -c SHA256SUMS.txt
```

---

## Code Signing & Security Notice

- **Windows Packages**: Binaries and installers are built directly from open-source repositories via automated workflows. Kernel UDE drivers (`usbip2_ude.sys`, `usbip2_filter.sys`) are Microsoft WHQL-certified and counter-signed by Microsoft Time-Stamp Service.
- **Android Packages**: APK builds are signed with the project release keystore and support direct sideloading on Android phones, tablets, and Android TV / Nvidia Shield.
- **macOS Packages**: Native Swift Universal binaries with IOKit device bridge, LaunchDaemon system persistence, and Menu Bar Extra support.

---

## License

All software components in the USBAnywhere suite are licensed under the **GNU General Public License v3.0 (GPL-3.0)**.
