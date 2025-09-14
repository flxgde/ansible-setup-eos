# 🚀 EndeavourOS Hyprland Setup with Ansible

This repository contains an **Ansible playbook** that automates my personal EndeavourOS setup from a clean installation — with no preinstalled desktop environment — into a fully customized, Hyprland-based workstation.

## 🖥️ What This Playbook Sets Up

- **Window Manager:** [Hyprland](https://hyprland.org)
- **Terminal:** [Ghostty](https://ghostty.org)
- **Editor:** [Neovim](https://neovim.io)
- **Browser:** [Zen Browser](https://zen-browser.app)
- **Email Client:** [Thunderbird](https://www.thunderbird.net)
- **Essential Tools:** (git, zsh, curl, etc.)
- **Custom Configurations:** Dotfiles and configs for:
  - Hyprland (keybinds, workspaces, theme)
  - Neovim (plugins, LSP, keymaps)
  - Ghostty (colors, fonts)
  - System utilities (aliases, shell configs)

## 📦 Requirements

- A **fresh installation of EndeavourOS** with **no desktop environment**.
- `python` installed (required for Ansible).
- SSH access enabled (or local access).
- Internet connection.

> ⚠️ This playbook assumes a clean system and may overwrite existing configuration files in `$HOME`.

## 🛠️ Setup Instructions

1. **Install Git & Ansible:**
   ```bash
   sudo pacman -S git ansible

