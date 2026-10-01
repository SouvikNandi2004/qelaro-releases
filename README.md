<div align="center">

# Qelaro Browser
### Ultra-Premium, Next-Generation Web Browser Engineered for Modern Desktops and Foldable Devices

<p align="center">
  <a href="https://github.com/SouvikNandi2004/qelaro-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/SouvikNandi2004/qelaro-releases?color=059669&label=Release&style=flat-square" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/badge/macOS-Apple%20Silicon%20%7C%20Intel-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS Support" />
  <img src="https://img.shields.io/badge/Windows-64--bit-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows Support" />
  <img src="https://img.shields.io/badge/Linux-AppImage%20%7C%20deb-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux Support" />
  <img src="https://img.shields.io/badge/License-Proprietary-475569?style=flat-square" alt="License" />
</p>

<p align="center">
  <a href="#download-and-installation">Download</a> &bull;
  <a href="#core-features">Features</a> &bull;
  <a href="#installation-instructions">Installation</a> &bull;
  <a href="#whats-new-in-v1012">Release Notes</a> &bull;
  <a href="https://qelaro.in">Official Website</a>
</p>

---

</div>

## Overview

Qelaro Browser is a modern desktop web browser engineered on top of Chromium and Electron architectures. Tailored specifically for multi-tasking workflows, dual-screen hardware, and foldable computing devices, Qelaro integrates process-isolated WebContents, low-latency GPU rasterization, and seamless extension compatibility into a unified, glassmorphic design.

This public repository serves as the official distribution channel for binary installers, update manifests, and verified cryptographic checksums.

---

## Core Features

### High-Performance Rendering Pipeline
- Built on Chromium with hardware-accelerated GPU rasterization.
- Low-latency zero-copy memory management providing fluid 60 FPS and 120 FPS display support.
- Optimized memory management ensuring low CPU and battery overhead during heavy multi-tab workflows.

### Foldable and Flex Mode Hardware Adaptation
- Dynamic posture recognition (flat, laptop, tent, book) for convertible and dual-screen displays.
- Responsive layout transitions that realign tab strips, split viewports, and omnibox controls without reload penalties.

### Multi-View Split Screen
- Side-by-side viewports in a single window with independent scrolling, zooming, and audio states.
- Drag-and-drop tab detachment and cross-window tab transference.

### Chrome WebExtensions Compatibility Bridge
- Native WebExtensions bridge supporting Chrome extensions (unpacked folders and packed packages).
- Dedicated extension action toolbar, dynamic badge counts, contextual menus, and secure popup dialogs.

### Privacy and Session Security
- Tracker protection and private browsing modes with zero disk trace.
- Strict cross-origin process isolation and secure credential storage.
- Zero telemetry tracking.

### Atomic Background Auto-Updater
- Silent update detection via verified release feeds.
- 1-click update installation with atomic swap and instant relaunch.
- Complete preservation of user data, history, cookies, and preferences across updates.

---

## Download and Installation

Official release packages are published below. Direct downloads do not require authentication or a GitHub account.

### Official Installers (Latest & v1.0.12)

> **Auto-Detection:** Clicking the download links below automatically delivers the verified release files directly from GitHub Releases.

| Platform | Architecture | Package Format | Direct Download | Checksum |
| :--- | :--- | :--- | :--- | :--- |
| **Windows** | 64-bit (x64) | `.exe` Setup Installer | [Qelaro-Setup-1.0.12-x64.exe](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-Setup-1.0.12-x64.exe) | [SHA-256](#cryptographic-verification) |
| **Windows** | 64-bit (x64) | `.exe` Portable (No Install) | [Qelaro-Portable-1.0.12-x64.exe](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-Portable-1.0.12-x64.exe) | [SHA-256](#cryptographic-verification) |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | `.dmg` Installer | [Qelaro-1.0.12-mac-arm64.dmg](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-1.0.12-mac-arm64.dmg) | [SHA-256](#cryptographic-verification) |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | `.zip` Archive | [Qelaro-1.0.12-mac-arm64.zip](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-1.0.12-mac-arm64.zip) | [SHA-256](#cryptographic-verification) |
| **macOS** | Intel Core (x64) | `.dmg` Installer | [Qelaro-1.0.12-mac-x64.dmg](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-1.0.12-mac-x64.dmg) | [SHA-256](#cryptographic-verification) |
| **Linux** | 64-bit (x64) | `.AppImage` | [Qelaro-1.0.12-x86_64.AppImage](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/Qelaro-1.0.12-x86_64.AppImage) | [SHA-256](#cryptographic-verification) |
| **Linux** | 64-bit (x64) | `.deb` (Debian/Ubuntu) | [qelaro_1.0.12_amd64.deb](https://github.com/SouvikNandi2004/qelaro-releases/releases/download/v1.0.12/qelaro_1.0.12_amd64.deb) | [SHA-256](#cryptographic-verification) |
| **All Platforms** | All Architectures | Full Release Hub | [View Latest GitHub Release ↗](https://github.com/SouvikNandi2004/qelaro-releases/releases/latest) | Auto-Detects |

---

## Installation Instructions

### macOS Installation
1. Download the `Qelaro-1.0.12-mac-arm64.dmg` package.
2. Open the disk image and drag **Qelaro.app** into your `/Applications` directory.
3. Open Qelaro from Applications or Spotlight.
4. *Gatekeeper Notice:* If prompted by macOS Gatekeeper on initial launch, right-click (or Control-click) `Qelaro.app` and choose **Open**, or run the following command in Terminal:
   ```bash
   xattr -cr /Applications/Qelaro.app
   ```

### Windows Installation
1. Download the Windows installer (`.exe`).
2. Run the executable and proceed through the setup wizard.
3. Launch Qelaro from the Start Menu or Desktop shortcut.

### Linux Installation
1. Download the `.AppImage` package.
2. Grant executable permissions and launch:
   ```bash
   chmod +x Qelaro-1.0.12-x86_64.AppImage
   ./Qelaro-1.0.12-x86_64.AppImage
   ```

---

## What's New in v1.0.12

### Initial Stable Release Highlights
* Fixed: Startup stall/freeze caused by synchronous live news feed bridge calls on WebView JS thread (replaced with non-blocking concurrent coroutine fetching and cache-first startup)
* Fixed: Find on page bar clicks passing through to underlying website in bottom address bar mode (added active toolbar touch interception in TouchPassThroughWebView)
* Fixed: Active tab number counter synchronization on omnibar horizontal swipe gestures
* Fixed: New tab address bar search query bleeding across tab navigation and back-stack transitions
* Performance: Reduced mobile startpage news network latency from 24s to under 1s with parallel async fetch

---

## Cryptographic Verification

All binaries are cryptographically hashed to guarantee file integrity. You can verify your download using SHA-256:

### macOS / Linux Verification
```bash
shasum -a 256 Qelaro-1.0.12-mac-arm64.dmg
```

### Windows Verification (PowerShell)
```powershell
Get-FileHash -Algorithm SHA256 .\Qelaro-1.0.12-mac-arm64.dmg
```

### Official SHA-256 Checksums (v1.0.12)
```text
c49dde2535f55668d887607a3e42ff9a06efac488bc108b84552a91c0693bc5e  Qelaro-1.0.12-mac-arm64.dmg
aa42f0f2f5f9e64c1cd2a0ed9a7cdd122fa26ca38c3968c85642eeb76e803ded  Qelaro-1.0.12-mac-arm64.zip
```

---

## Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Engine Core** | Chromium runtime |
| **Application Layer** | Electron multi-process framework |
| **Architectures** | ARM64 (Apple Silicon), x86_64 (Intel/AMD) |
| **Operating Systems** | macOS 12+, Windows 10/11 (64-bit), Ubuntu 20.04+ / Debian 11+ |
| **Hardware Requirements** | 2 GB RAM minimum, 4 GB RAM recommended |

---

## Support and Contact

- **Website:** [https://qelaro.in](https://qelaro.in)
- **Support:** [support@qelaro.in](mailto:support@qelaro.in)
- **Report an Issue:** Use the in-app feedback dialog via Help > Report an Issue, or contact customer support directly.

---

<div align="center">
<sub>Copyright &copy; 2026 Qelaro. All rights reserved.</sub>
</div>
