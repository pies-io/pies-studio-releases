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
