# 🌌 NYXOSx64  
A Modern Desktop Environment EXE by NYX Studios

NYXOSx64 is a custom desktop environment and launcher built by **NYX Studios** for 64-bit Windows systems.  
Right now it ships as a **compiled .exe only** (no source code included yet), with plans to make it **open source in the future** once things are stable and cleaned up.

> **Status:** Closed-source, proprietary EXE for now.  
> **Planned:** Public source release later under a proper license.

---

## ✨ What NYXOSx64 Does

### 🖥 Custom Desktop Environment
- Runs as its own desktop-style interface on top of Windows
- Clean NYX UI with a minimal, modern layout
- Designed for smooth daily use, not just a demo

### 🎨 Themes & Personalization
- Multiple built-in visual themes
- NYX-style accent colors and layout choices
- Saves your appearance preferences between sessions

### 🖼 Wallpaper Handling
- Lets you set and keep a custom wallpaper inside NYXOSx64
- Aimed at high-resolution setups
- Keeps your look consistent when you relaunch the EXE

### 📂 NYX Panel / Start Area
- Central NYX button / panel for quick access areas
- Room for shortcuts, user interface modules, and future add-ons
- Gives an OS-like feel without messing with core Windows files

---

## 🧰 System Requirements

- **OS:** Windows 10 or Windows 11 (64-bit)
- **CPU:** x64 processor
- **RAM:** 4 GB minimum (8+ GB recommended)
- **Disk:** A few hundred MB free for the app and its data

---

## 🚀 How to Run NYXOSx64

1. Download `NYXOSx64.exe` from the official release location.  
2. Put it in a dedicated folder (for example: `C:\NYXOSx64\`).  
3. Double-click `NYXOSx64.exe`.  
4. Set up your theme, wallpaper, and other options inside the app.

> There is **no supported Python/source run mode right now** for the public.  
> The distributed product is the **EXE only**.

---

## 🔓 Open Source Plans

NYXOSx64 is currently **closed-source** and fully protected under NYX Studios’ proprietary license.

Planned path (no ETA promised, but this is the direction):

- Clean up internal codebase  
- Strip anything sensitive / environment-specific  
- Release a **public, open-source** version of the core under a proper license  
- Keep some advanced/pro-only features separate if needed  

When that happens, this repo will be updated to include:

- The actual source code  
- Build instructions  
- Open-source license details  

Until then: **assume EXE-only, no source distribution rights.**

---

## 📁 Repo / File Layout (High-Level)

This is the intended structure for the repo side, not the full internal build tree:

```text
NYXOSx64/
 ├── NYXOSx64.exe          # Main compiled binary (release artifact)
 ├── assets/               # Public-safe images/icons if you choose to include them
 ├── data/                 # Local config/settings (created at runtime)
 ├── LEGAL/                # Full legal + policy pack
 │    ├── LICENSE
 │    ├── EULA.md
 │    ├── TERMS.md
 │    ├── PRIVACY.md
 │    ├── SECURITY.md
 │    ├── DMCA.md
 │    ├── NOTICE
 │    ├── SUPPORT.md
 │    └── CODE_OF_CONDUCT.md
 └── README.md
