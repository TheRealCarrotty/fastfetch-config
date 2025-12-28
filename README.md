<div align="center">

# ⚡ Fastfetch Config

*Clean, minimal system information display for your terminal*

</div>

## 👀 Preview

<table>
<tr>
<td align="center">
<img src="https://github.com/dacrab/fastfetch-config/assets/97808411/f249aabf-6850-4c45-938e-2a364c64b5ea" width="400"/>
<br><em>Linux</em>
</td>
<td align="center">
<img src="https://github.com/dacrab/fastfetch-config/assets/97808411/6f4b7f2b-989b-4f90-bd71-183dd00f0d0f" width="400"/>
<br><em>Windows</em>
</td>
</tr>
</table>

## 🚀 Install

**1. Install Fastfetch**
```bash
# Arch
sudo pacman -S fastfetch

# Ubuntu/Debian
sudo add-apt-repository ppa:fastfetch-devs/fastfetch
sudo apt update && sudo apt install fastfetch

# macOS
brew install fastfetch

# Windows
scoop install fastfetch
```

**2. Install Config**
```bash
# Linux/macOS
curl -fsSL https://raw.githubusercontent.com/dacrab/fastfetch-config/main/config.jsonc -o ~/.config/fastfetch/config.jsonc

# Windows (PowerShell)
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/dacrab/fastfetch-config/main/config.jsonc" -OutFile "$env:APPDATA\fastfetch\config.jsonc"
```

**3. Install Nerd Font**

Download and install any [Nerd Font](https://www.nerdfonts.com/) for proper icons.

**4. Run**
```bash
fastfetch
```

## ✨ Features

- System info (OS, kernel, uptime, packages)
- Hardware specs (CPU, GPU, memory, disk)  
- Desktop environment details
- Color palette display

## 🎨 Customize

Edit the config file:
- **Linux/macOS**: `~/.config/fastfetch/config.jsonc`
- **Windows**: `%APPDATA%\fastfetch\config.jsonc`

See [Fastfetch docs](https://github.com/fastfetch-cli/fastfetch/wiki/Configuration) for options.

---

<div align="center">

*Made with ❤️ for terminal enthusiasts*

</div>
