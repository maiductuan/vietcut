# 🎬 VietCut - High-Performance AI-Powered Desktop Video Editor

[![Release](https://img.shields.io/github/v/release/maiductuan/vietcut?style=flat-square&color=cyan)](https://github.com/maiductuan/vietcut/releases)
[![Downloads](https://img.shields.io/github/downloads/maiductuan/vietcut/total?style=flat-square&color=brightgreen)](https://github.com/maiductuan/vietcut/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue?style=flat-square)](https://github.com/maiductuan/vietcut/releases)
[![Built with Rust](https://img.shields.io/badge/built%20with-Rust%20%7C%20Tauri%20v2-orange?style=flat-square)](https://tauri.app/)
[![License](https://img.shields.io/badge/license-MIT%20%2F%20Free-green?style=flat-square)](#)

> **VietCut** is a blazing-fast, lightweight, and privacy-focused desktop video editor built with **Rust**, **Tauri v2**, **React**, and **FFmpeg Hardware Acceleration**. Designed for creators worldwide, it brings state-of-the-art local AI features directly to your PC—without cloud latency, subscription fees, or data leaks.

---

## ✨ Key Highlights

- **🔒 100% Local & Privacy-First**: All videos, audios, waveforms, and project data are processed entirely on your local machine. No media is ever uploaded to the cloud.
- **🎯 Pixel-Perfect WYSIWYG (What You See Is What You Get)**: What you preview in real-time is 100% identical to the final rendered video via FFmpeg filter-chain synchronization.
- **🤖 Offline AI Speech-to-Text Subtitles**: Generate automatic subtitles with high accuracy using local Whisper AI models. Supports Vietnamese, English, Chinese, and bilingual layout options.
- **🎙️ AI Voice Isolation & Noise Removal**: Isolate vocals, extract background music, or eliminate ambient noise in one click.
- **⚡ Hardware-Accelerated GPU Rendering**: Blazing-fast 1080p and 4K exports powered by NVIDIA NVENC, Intel QuickSync, and AMD AMF.
- **🎚️ Pro Multi-Track Timeline**: Seamlessly stack video overlays (PiP), audio stems, dynamic text overlays, and real-time transition effects with magnet snapping.

---

## 📥 Download & Installation

Get the latest installer for Windows (64-bit):

👉 **[Download VietCut v0.1.1 (.MSI Installer)](https://github.com/maiductuan/vietcut/releases/latest)**

### Quick Setup:
1. Download `VietCut_0.1.1_x64.msi`.
2. Double-click the installer and follow the on-screen setup wizard.
3. Launch **VietCut** from your Desktop or Start Menu and start creating!

---

## ⌨️ Essential Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Space` | Play / Pause playback |
| `Ctrl + B` | Split clip at current playhead position |
| `Delete` / `Backspace` | Delete selected clip(s) |
| `Ctrl + D` | Duplicate selected clip |
| `Ctrl + Z` / `Ctrl + Y` | Undo / Redo history |
| `Ctrl + Shift + S` | Quick extract audio from video to a separate track |
| `J` / `K` / `L` | Shuttle backward, stop, and shuttle forward |
| `Home` / `End` | Jump playhead to project start / end |
| `Ctrl + S` | Manual project save (auto-save is also active) |

---

## 💻 System Requirements

| Specification | Minimum | Recommended |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit) or Windows 11 | Windows 11 (64-bit) |
| **Processor (CPU)** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or higher |
| **Memory (RAM)** | 4 GB | 8 GB or 16 GB |
| **Storage** | 2 GB available space | 5 GB SSD storage |
| **Graphics (GPU)** | Integrated Intel HD Graphics | Dedicated GPU (NVIDIA GTX 1050 / AMD RX 560+) |

---

## 🛠️ Architecture & Tech Stack

- **Core & Runtime**: Rust 2021 + Tauri v2 (ultra-low memory footprint, ~5MB binary size)
- **Frontend**: React 19 + TypeScript + Vite + Tailwind CSS
- **Media Engine**: Native FFmpeg with GPU encoder passthrough (`h264_nvenc`, `h264_qsv`, `h264_amf`)
- **Speech Engine**: Local OpenAI Whisper AI & Silero VAD for intelligent voice isolation

---

## 💬 Community & Feedback

- Found a bug or have a feature idea? Please open an [Issue](https://github.com/maiductuan/vietcut/issues).
- Want to contribute? Pull requests are always welcome!

---

*Made with ❤️ for video creators and storytellers.*
