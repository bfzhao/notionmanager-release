# NotionManager Releases

[![GitHub release](https://img.shields.io/github/v/release/bfzhao/notionmanager-release)](https://github.com/bfzhao/notionmanager-release/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/bfzhao/notionmanager-release/total)](https://github.com/bfzhao/notionmanager-release/releases)

**NotionManager** is a secure local-first desktop tool designed to back up, version, and browse your Notion workspace 100% offline without breaking your data structure.

> ⚡ **Why NotionManager? (Notion's Official Export Falls Short)**
> 
> - Notion's official Markdown/CSV export **breaks your database relations, rollups, and linked views**.
> - NotionManager builds a fully functional, clickable, and beautiful **offline replica** of your workspace. Your data stays 100% local, safe, and lightning-fast.

---

## 📦 Downloads

Click to download the latest GA build for your operating system directly:

| Platform | Recommended Installer | Notes |
|----------|------|-------|
| **Windows** | [⬇️ Download EXE Installer](https://github.com/bfzhao/notionmanager-release/releases/latest) or<br/>[⬇️ Download Portable Zip](https://github.com/bfzhao/notionmanager-release/releases/latest) | *For Windows 10 or above* |
| **macOS (M1/M2/M3)** | [⬇️ Download Apple Silicon DMG](https://github.com/bfzhao/notionmanager-release/releases/latest) | *For modern Macs* |
| **macOS (Intel)** | [⬇️ Download Intel DMG](https://github.com/bfzhao/notionmanager-release/releases/latest) | *For older Macs* |
| **Linux** | [⬇️ Download AppImage](https://github.com/bfzhao/notionmanager-release/releases/latest) | *Universal, no install needed* |

> [!Note]
> * If your system warns about an "unverified developer" or "unknown publisher," that's that's expected for an unsigned build. Your data never leaves your machine. Just click "Run Anyway" or "Keep" to proceed.
> * If you are using any previous release (alpha/beta/rc), you should upgrade to the GA release since we only provide support for the GA release. A simple reinstall is all you need.

---

## 🛡️ Privacy & Security Commitments

Since this tool handles your Notion workspace, we take trust seriously:
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

If you run into a libfuse error on the latest Ubuntu, you may need to install libfuse manually first:

```bash
sudo apt update
sudo apt install libfuse2
```

---

## 🎁 Release Benefit

Use code **20CUTOFF** to get a 20% discount before Oct 16, 2026, 11:59:59 PM!

---

## 🐛 Report Issues

Found a bug or have a feature request? Please open an issue in the main repository:

👉 **[Submit an Issue](https://github.com/bfzhao/notionmanager-release/issues)**

## 📚 Documents & Tips

Please visit [notionmanager.com](https://notionmanager.com) to find more information regarding how to use NotionManager and protect your data. 
