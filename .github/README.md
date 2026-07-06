<p align="center">
  <img src="https://img.shields.io/badge/Compositor-Hyprland-blue?style=for-the-badge&logo=linux" alt="Hyprland">
  <img src="https://img.shields.io/badge/Shell-Quickshell-orange?style=for-the-badge&logo=qt" alt="Quickshell">
  <img src="https://img.shields.io/badge/Design-Material%20Design%203-green?style=for-the-badge&logo=android" alt="Material Design 3">
  <img src="https://img.shields.io/badge/License-GPL--3.0-red?style=for-the-badge" alt="GPL-3.0">
</p>

<h1 align="center">DroidDE</h1>

<p align="center">
An Android 16-inspired desktop environment built on <b>Hyprland</b> and <b>Quickshell</b>, bringing Material Design 3, fluid animations, and a tablet-first interface to Linux.
</p>

---

# Overview

> [!WARNING]
> **Hyprland 0.55+ Required**
>
> DroidDE targets **Hyprland 0.55 and newer**. If your distribution has not yet updated or you prefer the legacy Lua configuration format, switch to the **`Pre-Hyprland-Luaification`** branch.
>
> Running DroidDE on unsupported Hyprland versions may result in broken layouts or shell instability.

## What is DroidDE?

DroidDE is a complete desktop shell experience that recreates the look and feel of **Android 16** while remaining a traditional Linux desktop underneath.

Rather than replacing your operating system, DroidDE provides a highly customized collection of:

- Hyprland configuration
- Quickshell interface
- Material Design 3 styling
- Dynamic color generation
- Custom widgets
- Android-inspired layouts
- Installation and deployment scripts

The goal is to make Linux feel like using a modern Android tablet—without sacrificing desktop power.

## What DroidDE is **not**

DroidDE is **not**:

- ❌ A Linux distribution
- ❌ A custom kernel
- ❌ A desktop environment built from scratch

It **does not** manage:

- Display drivers
- PipeWire configuration
- Filesystems
- Bootloader configuration
- Base operating system setup

A working **Arch Linux** installation with Wayland support is expected before installation.

---

# Features

## 🎨 Material You Dynamic Colors

Generate a complete Material Design 3 color palette directly from your wallpaper.

Features include:

- Automatic wallpaper color extraction
- Dynamic accent generation
- Material You tonal palettes
- GTK theme recoloring
- Terminal color synchronization
- Live widget recoloring

Every major UI element updates automatically whenever your wallpaper changes.

---

## 📱 Android 16 Interface

Designed to closely mirror Google's latest tablet UI.

Highlights include:

- Split notification shade
- Dedicated quick settings panel
- Large Material Design 3 tiles
- Android-inspired app drawer
- Tablet dock/taskbar
- Gesture-oriented layouts
- Rounded Material components

---

## ⚡ Fluid Window Animations

Custom Hyprland animation curves provide smooth, natural movement throughout the desktop.

Animations include:

- Elastic workspace transitions
- Window spawn animations
- Smooth launcher opening
- Physics-inspired bezier curves
- Android-like motion throughout the interface

---

## 🤖 Built-in AI Workspace

Integrated AI utilities are available directly from the desktop.

Supports:

- Gemini API
- Ollama
- Local LLMs
- Quick prompt launcher
- Inline assistant panels

---

# Installation

> [!IMPORTANT]
> Before installing, ensure your package database is up to date and required dependencies such as `git`, `curl`, and `qt6-declarative` are installed.

## Quick Install

Install DroidDE directly from the bootstrap script.

```bash
bash <(curl -s https://droidde.link/get)
```

---

## Manual Installation

Recommended if you plan to customize or audit the configuration.

```bash
git clone --recursive https://github.com/dixon-team-tech/droid-de-hyprland.git

cd droid-de-hyprland

./setup install
```

---

# Default Keybindings

| Key | Action |
|------|--------|
| **Super + Enter** | Open terminal |
| **Super + /** | Open shortcut/search panel |
| **Super + D** | Toggle Android app drawer |
| **Super + N** | Open notification & quick settings shade |
| **Super + Q** | Close focused window |
| **Super + ← / →** | Switch workspaces |
| **Super + Shift + Float** | Toggle centered floating window |

---

# Software Stack

| Component | Purpose |
|------------|---------|
| **Hyprland** | Wayland compositor |
| **Quickshell** | QML desktop shell |
| **Qt6** | UI framework |
| **Fastfetch** | System information display |
| **Material Design 3** | Design language |
| **deps-info.md** | Package and dependency reference |

---

# Project Goals

DroidDE aims to provide:

- Android tablet aesthetics on Linux
- Modern Material Design 3 visuals
- Touch-friendly desktop layouts
- High-performance Wayland rendering
- Dynamic wallpaper-based theming
- A polished and cohesive desktop experience

Rather than simply imitating Android visually, DroidDE adapts Android's design philosophy to a desktop workflow while preserving the flexibility of Linux.

---

# Credits

Special thanks to everyone who contributed to the project.

### Contributors
- **@end-4** — Original Project Creator
- **@clsty** — Installer improvements and deployment stability
- **@midn8hustlr** — Material You color extraction enhancements
- **@outfoxxed** — Quickshell implementation and guidance

### Inspiration

DroidDE is heavily inspired by:

- Android 16
- Google Pixel Tablet UI
- Material Design 3
- The Hyprland ecosystem

### Core Projects

Special thanks to the maintainers of:

- Hyprland
- Quickshell
- AGS
- EWW
- Qt

Without these projects, DroidDE would not exist.

---

# License

DroidDE is licensed under the **GPL-3.0 License**.

You're welcome to:

- Fork the project
- Modify it
- Rebrand it
- Contribute improvements
- Build your own desktop experience on top of it

See the **LICENSE** file for complete license information.
