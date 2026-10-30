# PIES Studio Hobby

PIES Studio Hobby is a free desktop app for macOS, Windows and Linux that builds full applications from plain English, with a private AI that runs on your own computer.

## What is PIES Studio Hobby

PIES Studio Hobby is a complete application builder on your desktop: data model, screens, events, functions, sign-in, documents, PDF, a mobile app and AI agents, all from one definition. Build by describing what you want in plain English, or by hand in the visual editor; both produce the same application. PIES Private AI Micro, a language model that runs on your own computer, is included and free, and it makes no network calls. Hobby works offline and is free forever: it is the same editor as Enterprise, not a trial, and a free PIES account is needed only to download it.

**Honest limits:** PIES Private AI Micro handles chat, questions over your data, in-app chatbots, small edits and building one screen, data model or event at a time. Whole-application builds need a bigger model: your own cloud AI key, or PIES Enterprise or PIES Cloud. Hobby is for one person. PIES Studio is not open source; Hobby is free to use, and the source of the apps you build is yours.

## Download

- **[pies.io/download](https://pies.io/download/)** (free account)
- **[Latest release on GitHub](../../releases/latest)**: see the platform table below for which file to pick.

## Requirements

macOS 13 or later (Apple Silicon or Intel), Windows 10 or 11 64-bit, or Linux x64. 8 GB of memory for the Studio alone, 12 GB minimum and 16 GB recommended with Private AI Micro switched on. About 3 GB of disk for the app, plus 6 GB for the optional local model.

## Compare, docs and help

- Compare PIES Studio with other AI app builders: <https://pies.io/compare/>
- Docs: <https://docs.pies.io>
- Discord: <https://discord.gg/wAD8F2udg>
- Support: <support@pies.io>

---

# PIES Studio Desktop — Releases

Official installers for **PIES Studio Desktop**, the offline low-code IDE.
This repository hosts release binaries only — it contains no source code.

👉 **[Download the latest release](../../releases/latest)**

## Platforms

| Platform | File | Notes |
|---|---|---|
| **macOS** (Apple Silicon) | `.dmg` | Signed and notarized by Apple — opens with no warning. |
| **Windows** 10/11 (64-bit) | `Setup .exe` | Installer wizard. Currently unsigned: SmartScreen shows "Windows protected your PC" → **More info → Run anyway**. |
| **Ubuntu / Debian** | `.deb` | Double-click to install; appears in your applications menu. |
| **Any Linux** | `.AppImage` | No installation — `chmod +x` and run. |

## What's included

PIES Studio Desktop runs the **entire platform on your machine**: the visual
IDE, an embedded database, live preview, and the AI build agent. The installer
bundles every runtime it needs — Go, Node, bun, MySQL, MongoDB and Valkey — so
**no developer tools are required** on the host.

## System requirements

- **macOS** 12+ on Apple Silicon (M1 or later)
- **Windows** 10/11, 64-bit
- **Linux** x86-64, glibc 2.28+ (Ubuntu 20.04+ or equivalent)
- ~8 GB free disk space, 8 GB RAM minimum (16 GB recommended)

## Support

Website: <https://pies.io>
