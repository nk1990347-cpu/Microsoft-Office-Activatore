# 🔑 Microsoft Office KMS Activation Tool (AE Creation)

> A powerful, automated Windows command-line utility packaged as a **Standalone Executable (`.exe`)** for auto-detecting, verifying, and activating Microsoft Office versions (2010 through 2021) via KMS servers.

<div align="center">

[![Platform: Windows](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)](https://github.com/nk1990347-cpu/Microsoft-Office-Activatore)
[![Privileges: Admin Required](https://img.shields.io/badge/Privileges-Administrator-red?style=for-the-badge&logo=windows-terminal)](https://github.com/nk1990347-cpu/Microsoft-Office-Activatore)
[![Release: Standalone EXE](https://img.shields.io/badge/Release-v1.0.0-orange?style=for-the-badge&logo=github)](https://github.com/nk1990347-cpu/Microsoft-Office-Activatore/releases/tag/V1.0.0)

</div>

---

## 📥 Quick Download

* **[⬇️ Download `default.exe` (v1.0.0)]([https://github.com/nk1990347-cpu/Microsoft-Office-Activatore/releases/download/V1.0.0/default.exe])(https://github.com/nk1990347-cpu/Microsoft-Office-Activatore/releases/download/V1.0.0/AE-Apps_MS-Office-Activatore.exe))**
* **[📦 View All Releases](https://github.com/nk1990347-cpu/Microsoft-Office-Activatore/releases/tag/V1.0.0)**

> **Note:** Zero setup or Python installation is required. Simply download the standalone `.exe` and run it as Administrator!

---

## ✨ Key Features & Specializations

* **⚡ Standalone EXE:** Fully compiled into a ready-to-run Windows executable—no Python runtime or additional package installation required.
* **🛡️ Auto-Elevation Handling:** Automatically detects missing administrative rights and triggers Windows UAC prompt for admin execution.
* **🔍 Smart Detection Engine:** 
  * Automatically scans the Windows Registry to detect installed Office versions (2010, 2013, 2016, 2019, 2021).
  * Automatically locates installation paths and verifies the presence of `OSPP.VBS`.
  * Scans installed product suites (Word, Excel, PowerPoint, Visio, Project).
* **📡 KMS Health Check:** Tests connectivity to KMS servers over port `1688` before initiating activation.
* **🔄 Execution Flexibility:** Supports 1-Click Automatic Execution, manual command display, and saving generated scripts directly as `.bat` files.
* **🎨 System Integration & Icon Detection:** Includes automatic icon presence checking across Windows Taskbar, Task Manager, Shortcuts, and Dock applications (Winstep Nexus / RocketDock).

---

## 🛠️ Tech Stack & Build Environment

* **Language / Core:** Python 3.x, Windows Management Registry, `subprocess`, `socket`, `ctypes`
* **Packaging:** PyInstaller / Auto PY to EXE (compiled to standalone `.exe`)
* **System Requirements:** Windows OS (Run as Administrator)

---

## 🚀 How to Use

1. Download the latest standalone **`default.exe`** from the [Releases Page](https://github.com/nk1990347-cpu/Microsoft-Office-Activatore/releases/tag/V1.0.0).
2. Right-click the `.exe` and select **Run as administrator** (or allow the app's auto-elevation prompt).
3. Follow the interactive menu prompts:
   * Confirm or select your Microsoft Office version.
   * Choose your specific edition (Standard, Professional Plus, Visio, Project).
   * Select an online KMS server.
4. Choose **Automatic Execution** to activate instantly, or export to a `.bat` script.

---

## 👨‍💻 Author & Support

* **Developer:** AE Creation / AE-Apps (Naveen Kumar S)
* **Email:** `aecreationapps@gmail.com`
