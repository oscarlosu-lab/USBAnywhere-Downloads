# USBAnywhere — Official Distribution & Mirror Archive

This repository serves as the centralized backup mirror and distribution archive for releases across the USBAnywhere open-source ecosystem.

Official releases, source code, issue trackers, and technical discussions are hosted in their respective primary repositories:

- **Windows Client**: [oscarlosu-lab/USBAnywhere](https://github.com/oscarlosu-lab/USBAnywhere)
- **Windows Server**: [oscarlosu-lab/USBAnywhere-Server](https://github.com/oscarlosu-lab/USBAnywhere-Server)
- **Android & Android TV**: [oscarlosu-lab/USBAnywhere-Android](https://github.com/oscarlosu-lab/USBAnywhere-Android)
- **Web Portal & Documentation**: [oscarlosu-lab.github.io/USBAnywhere](https://oscarlosu-lab.github.io/USBAnywhere/)
- **Community Forum**: [r/UsbAnywhere](https://www.reddit.com/r/UsbAnywhere/)

---

## Current Stable Releases

### 1. USBAnywhere Client (Windows 10 / 11)

**Version 3.1.0** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere/releases/tag/v3.1.0) | [Mirror Release](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/tag/client-v3.1.0)

| Package | Architecture | Format | Download Link |
|---|---|---|---|
| Windows Installer | x64 | Setup EXE | [USBAnywhere_Setup_v3.1.0.exe](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/client-v3.1.0/USBAnywhere_Setup_v3.1.0.exe) |
| Portable Archive | x64 | ZIP | [USBAnywhere-v3.1.0-x64.zip](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/client-v3.1.0/USBAnywhere-v3.1.0-x64.zip) |
| Portable Archive | ARM64 | ZIP | [USBAnywhere-v3.1.0-arm64.zip](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/client-v3.1.0/USBAnywhere-v3.1.0-arm64.zip) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/client-v3.1.0/SHA256SUMS.txt) |

---

### 2. USBAnywhere Server (Windows 10 / 11)

**Version 3.1.0** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere-Server/releases/tag/v3.1.0) | [Mirror Release](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/tag/server-v3.1.0)

| Package | Architecture | Format | Download Link |
|---|---|---|---|
| Windows Installer | x64 | Setup EXE | [USBAnywhere-Server_Setup_v3.1.0.exe](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/server-v3.1.0/USBAnywhere-Server_Setup_v3.1.0.exe) |
| Portable Archive | x64 | ZIP | [USBAnywhere-Server-v3.1.0-x64-Portable.zip](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/server-v3.1.0/USBAnywhere-Server-v3.1.0-x64-Portable.zip) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/server-v3.1.0/SHA256SUMS.txt) |

---

### 3. USBAnywhere Android & Android TV

**Version 1.0.1** — [Primary Release Page](https://github.com/oscarlosu-lab/USBAnywhere-Android/releases/tag/v1.0.1) | [Mirror Release](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/tag/android-v1.0.1)

| Package | Platform | Format | Download Link |
|---|---|---|---|
| Standalone Sideload Package | Android 8.0+ / Android TV | APK (2.07 MB) | [USBAnywhere-Android-v1.0.1.apk](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/android-v1.0.1/USBAnywhere-Android-v1.0.1.apk) |
| Google Play App Bundle | Android 8.0+ / Android TV | AAB (4.26 MB) | [USBAnywhere-Android-v1.0.1.aab](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/android-v1.0.1/USBAnywhere-Android-v1.0.1.aab) |
| SHA-256 Checksums | All | TXT | [SHA256SUMS.txt](https://github.com/oscarlosu-lab/USBAnywhere-Downloads/releases/download/android-v1.0.1/SHA256SUMS.txt) |

---

## Verifying Integrity

To verify the integrity of any downloaded package against its published SHA-256 checksum:

### Windows (PowerShell)
```powershell
Get-FileHash .\USBAnywhere_Setup_v3.1.0.exe -Algorithm SHA256
```

### Linux / macOS
```bash
sha256sum -c SHA256SUMS.txt
```

---

## Code Signing & Security Notice

- **Windows Packages**: Binaries and installers are built directly from open-source repositories via automated workflows. Windows Defender SmartScreen may display an unknown publisher notice until developer certificates are acquired.
- **Android Packages**: APK builds are signed with the project release keystore and support direct sideloading. Enable *Install Unknown Apps* in Android Settings if prompted during manual installation.

---

## License

All software components in the USBAnywhere suite are licensed under the **GNU General Public License v3.0 (GPL-3.0)**.
