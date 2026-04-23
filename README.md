# i3 Dotfiles (Rice Setup)

This repository contains my customized **i3 window manager setup (rice)** built on Linux.  
It includes a minimal, fast, and aesthetic tiling workflow setup inspired by productivity-focused environments.

---

## 🧠 About This Setup

This rice was built through hands-on Linux customization, focusing on:
- Lightweight performance
- Keyboard-driven workflow
- Clean and minimal UI
- Fast development environment

It is designed for daily use, development, and multitasking.

---

## 🪟 Window Manager

- i3wm (tiling window manager)
- Custom keybindings for productivity
- Workspace-based workflow

---

## 🎨 Included Configurations

- i3 window manager config
- Polybar (status bar setup)
- Rofi (application launcher)
- Alacritty (terminal emulator)
- Picom (compositor for transparency/animations)
- Systemd user services (where needed)

---

## 📁 Structure

.config/
├── i3/
├── polybar/
├── rofi/
├── alacritty/
├── picom/
└── systemd/user/


---

## ⚙️ Features

- Lightweight tiling workflow
- Fast app launching with Rofi
- Custom bar (Polybar)
- Transparent terminal effects (Picom)
- Keyboard-driven navigation
- Minimal distractions setup

---

## 🚀 Installation (Manual)

Clone this repository:

```bash
git clone https://github.com/Karen64345/i3_dotfile.git
cd i3_dotfile
```
Then copy configs:
```
cp -r .config/* ~/.config/
```
Reload i3:
```
Mod + Shift + R
```

⚠️ Notes
This setup was built on Arch Linux and CachyOs
Some packages may need manual installation depending on your distro
Do NOT commit browser data or system cache files (already cleaned)
