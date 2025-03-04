# 🖥️ NixOS .dotfiles

**My personal NixOS configuration files (Work in Progress)**  

---

## 🛠️ Current Contents

### Configuration Modules
- **NixOS**: System configuration (`nixos/`)


### Key Features
- NixOS integration for declarative configuration
- Modular structure for easy component management
---

## ⚠️ Work in Progress Notice

This configuration is **actively evolving** and may contain:
- Unfinished configuration modules
- Experimental NixOS components
- Temporary workarounds
- Documentation gaps

**Current TODOs:**
- [ ] Complete Hyprland Wayland setup
- [ ] Add more application configurations
- [ ] Setup neovim
- [ ] Add a Kanagawa inspired theme
---

## ⚡ Installation

This should allow you to install my dotfiles to a fresh NixOS system:
```bash
nix-shell -p git --command "nix run --experimental-features 'nix-command flakes' github:DimitriosNicolay/.dotfiles" ~/.dotfiles
```

---

## 🌟 Inspiration & Credits

This configuration started with **[LibrePhoenix](https://github.com/LibrePhoenix)**'s NixOS config.
Check out his Youtube and Blog!
- [LibrePhoenix' YouTube Channel](https://www.youtube.com/@LibrePhoenix) 🎥  
- [LibrePhoenix Blog](https://librephoenix.com/) ✍️  

---
