# NotionManager Releases

[![GitHub release](https://img.shields.io/github/v/release/bfzhao/notionmanager-release)](https://github.com/bfzhao/notionmanager-release/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/bfzhao/notionmanager-release/total)](https://github.com/bfzhao/notionmanager-release/releases)

**NotionManager** is a secure, local-first desktop tool designed to back up, version, and 100% offline-browse your Notion workspace without breaking your data structure.



> ⚡ **Why NotionManager? (The Official Export Pain)**
> 
> - Notion's official Markdown/CSV export **completely breaks your database relations, rollups, and linked views**.
> - NotionManager builds a fully functional, clickable, and beautiful **offline replica** of your workspace. Your data stays 100% local, safe, and lightning-fast.

---

## 📦 Downloads

Click to download the latest stable Alpha build for your operating system directly:

| Platform | Recommended Installer | Alternative Option |
|----------|------|-------|
| **Windows** | [⬇️ Download EXE Installer](https://github.com/bfzhao/notionmanager-release/releases/latest) | [⬇️ Download Portable Zip](https://github.com/bfzhao/notionmanager-release/releases/latest) |
| **macOS (M1/M2/M3)** | [⬇️ Download Apple Silicon DMG](https://github.com/bfzhao/notionmanager-release/releases/latest) | *For modern Macs* |
| **macOS (Intel)** | [⬇️ Download Intel DMG](https://github.com/bfzhao/notionmanager-release/releases/latest) | *For older Macs* |
| **Linux** | [⬇️ Download AppImage](https://github.com/bfzhao/notionmanager-release/releases/latest) | *Universal, no install needed* |

> **Note**: If your system warns about an "unverified developer" or "unknown publisher," that's normal for an early Alpha. Your data never leaves your machine. Just click "Run Anyway" or "Keep" to proceed.

---

## 🛡️ Privacy & Security Commitments

Since this tool handles your Notion workspace workspace, we take trust seriously:
* **100% Local-First**: All data downloading, parsing, and offline caching happen entirely on your local machine.
* **No Cloud Uploads**: We never see, collect, or upload your Notion Access Tokens or page content to any third-party servers.

---

## 🚀 Quick Start

**Windows**  
Double-click the `.exe` file and follow the installation wizard.

**macOS**  
1. Open the `.dmg` file  
2. Drag `NotionManager.app` into the `Applications` folder

*As the release has not been officially signed yet, you may need to allow it explicitly: Go to System Settings → Privacy & Security → Security, then click **Open Anyway** for NotionManager.*

**Linux**  
```bash
chmod +x NotionManager.AppImage
./NotionManager.AppImage
```

In case you run into error on libfuse in latest ubuntu, you may need install libfuse manually at first:

```bash
sudo apt update
sudo apt install libfuse2
```

---

## 🎁 Early Tester Benefit

As an early Alpha tester, if this tool helps secure your data, please consider leaving your contact/feedback on our [Waitlist & Feedback](https://tally.so/r/81EEaA) Form. You will automatically receive a 50% Lifetime Discount Coupon when the stable version officially launches.

---

## 🐛 Report Issues

Found a bug or have a feature request? Please open an issue in the main repository:

👉 **[Submit an Issue](https://github.com/bfzhao/notionmanager-release/issues)**
