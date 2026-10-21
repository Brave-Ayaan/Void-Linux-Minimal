<div align="center">

# ⚡ Void Linux — Hyper-Minimal Niri Setup

*A lightweight, scrollable-tiling, keyboard-driven workflow built for speed.*

<p align="center">
  <a href="https://brave-ayaan.github.io"><b>🌐 Portfolio</b></a> •
  <a href="https://github.com/Brave-Ayaan"><b>🐙 GitHub Profile</b></a>
</p>

<br>

<!-- Core Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/OS-Void_Linux-478061?style=for-the-badge&logo=voidlinux&logoColor=white" alt="Void Linux" />
  <img src="https://img.shields.io/badge/Init-runit-1d2021?style=for-the-badge&logo=gnu&logoColor=white" alt="runit" />
  <img src="https://img.shields.io/badge/WM-Niri-2B303A?style=for-the-badge&logo=wayland&logoColor=white" alt="Niri" />
  <img src="https://img.shields.io/badge/Pkg_Manager-XBPS-008080?style=for-the-badge&logo=voidlinux&logoColor=white" alt="XBPS" />
</p>

<!-- Toolchain Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Terminal-Kitty-000000?style=for-the-badge&logo=kitty&logoColor=white" alt="Kitty" />
  <img src="https://img.shields.io/badge/Editor-LazyVim-57A143?style=for-the-badge&logo=neovim&logoColor=white" alt="LazyVim" />
  <img src="https://img.shields.io/badge/Browser-Qutebrowser-4285F4?style=for-the-badge&logo=qutebrowser&logoColor=white" alt="qutebrowser" />
  <img src="https://img.shields.io/badge/File_Manager-Yazi-D97706?style=for-the-badge&logo=yazi&logoColor=white" alt="Yazi" />
  <img src="https://img.shields.io/badge/Launcher-Fuzzel-E040FB?style=for-the-badge&logo=wayland&logoColor=white" alt="Fuzzel" />
  <img src="https://img.shields.io/badge/Bar-Waybar-00A8F0?style=for-the-badge&logo=wayland&logoColor=white" alt="Waybar" />
</p>

</div>

---

## 🖼️ Screenshots & Showcase

<div align="center">
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8be29640-ca31-4084-817f-5f240a03d2f8" />

### Main Desktop Overview
<img src="https://raw.githubusercontent.com/Brave-Ayaan/dotfiles/main/assets/desktop.png" alt="Desktop Overview" width="95%" style="border-radius: 8px;">
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3f125162-699b-4baa-b89d-383f14621930" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4360e23a-1f45-4f8a-95d0-036c9c249262" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4c75ae4f-e3de-4c13-baaa-496190774e23" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/26094eb3-247e-4a1c-a952-81fa50e7f590" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4fbf09f7-b6ce-4c47-b691-b46982b053a0" />

<br><br>

<table>
  <tr>
    <td width="50%" align="center">
      <b>LazyVim & Kitty</b><br><br>
      <img src="https://raw.githubusercontent.com/Brave-Ayaan/dotfiles/main/assets/editor.png" alt="LazyVim Setup" width="100%">
    </td>
    <td width="50%" align="center">
      <b>Yazi File Manager</b><br><br>
      <img src="https://raw.githubusercontent.com/Brave-Ayaan/dotfiles/main/assets/yazi.png" alt="Yazi TUI" width="100%">
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>Fuzzel Launcher</b><br><br>
      <img src="https://raw.githubusercontent.com/Brave-Ayaan/dotfiles/main/assets/fuzzel.png" alt="Fuzzel Launcher" width="100%">
    </td>
    <td width="50%" align="center">
      <b>Qutebrowser</b><br><br>
      <img src="https://raw.githubusercontent.com/Brave-Ayaan/dotfiles/main/assets/browser.png" alt="Qutebrowser" width="100%">
    </td>
  </tr>
</table>

</div>

---

## 🛠️ Minimal Toolchain Overview

> [!NOTE]
> Strictly built for speed and minimalism. Everything runs cleanly via **XBPS** and `runit`, utilizing **Niri**'s scrollable-tiling Wayland compositor alongside modal/vim-driven applications.

<details>
<summary><b>📋 Software Breakdown (Click to expand)</b></summary>

<br>

| Component | Software | Description |
| :--- | :--- | :--- |
| **OS** | [Void Linux](https://voidlinux.org/) | Rolling distribution (`x86_64`) |
| **Init System** | `runit` | Fast and lightweight service supervision |
| **Compositor / WM** | [Niri](https://github.com/YaLteR/niri) | Scrollable-tiling Wayland compositor |
| **Terminal** | [Kitty](https://sw.kovidgoyal.net/kitty/) | GPU-accelerated terminal emulator |
| **Editor** | [LazyVim](https://www.lazyvim.org/) | Neovim framework configured for fast editing |
| **Browser** | [qutebrowser](https://qutebrowser.org/) | Vim-bound, minimalist Python browser |
| **File Manager** | [Yazi](https://github.com/sxyazi/yazi) | Async TUI file manager written in Rust |
| **Launcher** | [Fuzzel](https://codeberg.org/dnkl/fuzzel) | Lightweight Wayland application launcher |
| **Bar** | [Waybar](https://github.com/Alexays/Waybar) | Customizable status bar |
| **Fallback WM** | [Sway](https://swaywm.org/) | i3-compatible Wayland compositor |

</details>

---

<p align="center">
  <a href="https://github.com/Brave-Ayaan/dotfiles/stargazers">
    <img src="https://img.shields.io/github/stars/Brave-Ayaan/dotfiles?style=for-the-badge&color=478061&logo=github" alt="Stars">
  </a>
  <a href="https://github.com/Brave-Ayaan/dotfiles/commits/main">
    <img src="https://img.shields.io/github/last-commit/Brave-Ayaan/dotfiles?style=for-the-badge&color=478061&logo=git" alt="Last Commit">
  </a>
</p>
