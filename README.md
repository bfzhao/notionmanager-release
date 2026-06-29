# NotionManager Releases

[![GitHub release](https://img.shields.io/github/v/release/bfzhao/notionmanager-release)](https://github.com/bfzhao/notionmanager-release/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/bfzhao/notionmanager-release/total)](https://github.com/bfzhao/notionmanager-release/releases)

NotionManager is a desktop tool that helps you back up, version, and offline-browse your Notion workspace.

---

## 📦 Downloads

Choose the file that matches your operating system:

| Platform | File | Notes |
|----------|------|-------|
| **Windows** | NotionManager-\<version\>-win-x64-installer.exe | Installer (recommended) |
| | NotionManager-\<version\>-win-x64-portable.exe | Portable (no install needed) |
| **macOS** | NotionManager-\<version\>-mac-arm64.dmg  | For M1/M2/M3 Macs |
|  | NotionManager-\<version\>-mac-x64.dmg   | For Intel CPU based Macs |
| **Linux** | NotionManager-\<version\>-linux-x86_64.AppImage | Universal, no install needed |

> **Note**: If your system warns about an "unverified developer" or "unknown publisher," that's normal for now. Just click "Run Anyway" or "Keep" to proceed.

---

## 🚀 Quick Start

**Windows**  
Double-click the `.exe` file and follow the installation wizard.

**macOS**  
1. Open the `.dmg` file  
2. Drag `NotionManager.app` into the `Applications` folder

As the release has not been official signed, you may need allow to run this explicitly. Go to System Settings → Privacy & Security → Security, then click Open Anyway for NotionManager.
After that, macOS should allow the app to run.

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

## 🐛 Report Issues

Found a bug or have a feature request? Please open an issue in the main repository:

👉 **[Submit an Issue](https://github.com/bfzhao/notionmanager-release/issues)**
