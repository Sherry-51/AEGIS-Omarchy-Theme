# AEGIS — Deep Space Command Center

<div align="center">

```
     ___     ______   _______  __      _______.
    /   \   |   ____| /  _____||  |    /       |
   /  ^  \  |  |__   |  |  __  |  |   |   (----`
  /  /_\  \ |   __|  |  | |_ | |  |    \   \    
 /  _____  \|  |____ |  |__| | |  |.----)   |   
/__/     \__\_______| \______| |__|_______/     
                                                
    DEEP SPACE COMMAND CENTER // OMARCHY LINUX
```

**An immersive, high-contrast, technical workstation theme for Omarchy Linux, Arch Linux, Hyprland, and Wayland.**

[![Omarchy 4.x](https://img.shields.io/badge/Omarchy-4.x-74d7e8?style=flat-square)](https://omarchy.org)
[![Hyprland](https://img.shields.io/badge/Hyprland-Wayland-3e6fa8?style=flat-square)](https://hyprland.org)
[![Contrast WCAG AAA](https://img.shields.io/badge/Contrast-15.08:1%20AAA-6fbf9c?style=flat-square)](#color-philosophy)
[![Wallpapers](https://img.shields.io/badge/Wallpapers-16%20Curated%201440p-8876b8?style=flat-square)](#curated-wallpaper-collection)
[![License: MIT](https://img.shields.io/badge/License-MIT-d6a85e?style=flat-square)](LICENSE)

</div>

---

## 🛰️ Overview

**AEGIS** transforms your Omarchy Linux installation into an advanced deep-space command console. Designed for systems programmers, cybersecurity researchers, and infrastructure engineers working in focused environments, AEGIS prioritizes:

- **Calm Focus:** Eliminates aggressive neon glare, visual clutter, and unnecessary animations.
- **Technical Authenticity:** Grounded in spacecraft telemetry, orbital mechanics, and scientific observation.
- **Maximum Ergonomics:** WCAG AAA 15.08:1 text contrast with carefully delineated semantic color roles.
- **Seamless Omarchy Integration:** 100% native schema support for Omarchy 4.x dynamic configuration and template engine.

---

## 🎨 Color Architecture

The AEGIS palette balances deep-space isolation with crisp, high-visibility telemetry accents:

| Token | Hex | Role | Semantic Meaning |
|---|---|---|---|
| `dark_background` | `#05070D` | Absolute Base | Deep space void canvas |
| `background` | `#080B14` | Primary Surface | Terminal and editor workstation canvas |
| `lighter_background` | `#0D1220` | Secondary Surface | Inactive panels, dividers, and meters |
| `selection` | `#1B2540` | Active Surface | Selected processes, visual selections, highlights |
| `foreground` | `#D9E2F2` | Primary Text | Clean cool-white text (15.08:1 contrast) |
| `light_foreground` | `#93A1B8` | Secondary Text | Metadata, status line items, secondary labels |
| `muted` | `#5E6B80` | Muted Text | Syntax comments, disabled UI states, line numbers |
| `accent` | `#74D7E8` | Primary Accent | Active selections, telemetry reticles, focus |
| `cursor` | `#A5EEF5` | Bright Accent | Primary cursor, active line numbers |
| `blue` | `#3E6FA8` | Mission Blue | Structural functions, navigation, CPU telemetry |
| `purple` | `#8876B8` | Cosmic Purple | Types, keywords, secondary network graphs |
| `green` | `#6FBF9C` | Emerald | Success states, healthy memory, verified status |
| `yellow` | `#D6A85E` | Amber | Elevated metrics, warnings, attention states |
| `red` | `#D16969` | Restrained Red | Critical telemetry alerts, errors, failures |

---

## 🌌 Curated Wallpaper Collection (16 Total)

AEGIS ships with **exactly 16 high-resolution (2560×1440 16:9)** wallpapers. The collection pairs authentic scientific imagery from NASA/ESA deep space missions with bespoke vector telemetry artwork:

| # | Filename | Description | Provenance |
|---|---|---|---|
| **01** | `01-command-center.png` | **Primary AEGIS Wallpaper** — Deep space command horizon with telemetry vectors | Original Bespoke Art |
| **02** | `02-earth-from-orbit.jpg` | Apollo 17 "Blue Marble" orbital Hasselblad scan | NASA (`as17-148-22727`) |
| **03** | `03-deep-space.jpg` | Hubble Ultra Deep Field (Thousands of ancient galaxies) | NASA / ESA (`PIA12110`) |
| **04** | `04-carina-nebula.jpg` | JWST NIRCam Cosmic Cliffs in Carina Nebula | NASA / ESA / STScI |
| **05** | `05-lunar-surface.jpg` | Apollo 11 lunar regolith with stark crater shadows | NASA (`as11-40-5875`) |
| **06** | `06-orbital-station.jpg` | ISS Cupola observation windows overlooking the void | NASA (`iss042e078481`) |
| **07** | `07-satellite-telemetry.jpg` | GRACE twin satellites measuring gravitational telemetry | NASA / JPL (`PIA04921`) |
| **08** | `08-earth-at-night.jpg` | Nile River basin & Mediterranean night city lights from ISS | NASA Earth Observatory |
| **09** | `09-starfield-minimal.png` | Sparse, tranquil micro-starfield on deep void canvas | Original Bespoke Art |
| **10** | `10-cosmic-horizon.jpg` | Cassini wide-angle view of Saturn's limb & ring shadows | NASA / JPL (`PIA08351`) |
| **11** | `11-scientific-observation.jpg` | James Webb Space Telescope gold primary mirror array | NASA / GSFC (`PIA11195`) |
| **12** | `12-cosmic-blue-abstract.png` | Orbital trajectory ellipses & gravitational vector fields | Original Bespoke Art |
| **13** | `13-the-void.png` | Ultra-dark isolation canvas with microscopic cosmic dust | Original Bespoke Art |
| **14** | `14-nebula-purple.jpg` | Bubble Nebula NGC 7635 in deep infrared wavelengths | NASA / JPL-Caltech / WISE |
| **15** | `15-deep-space-exploration.jpg` | Voyager spacecraft traversing interstellar space | NASA / JPL (`PIA14111`) |
| **16** | `16-aegis-signature.png` | Signature orbital telemetry platform overlooking celestial limb | Original Bespoke Art |

*Complete license details and original asset URLs are documented in [SOURCES.md](SOURCES.md).*

---

## 🛠️ Themed Applications & Components

- **Desktop Shell (Quickshell):** Top status bar, workspace indicators, application launcher, notifications, popups, and lock screen.
- **Window Management (Hyprland):** Dual-color gradient active border (`rgba(74d7e8ee) rgba(3e6fa8ee) 45deg`) and dark graphite inactive border (`rgba(141b2daa)`).
- **Terminals (Foot & Alacritty):** Deep-space background, ANSI 16-color palette, high-visibility cursor, and distinct selection.
- **Editor (Neovim):** Syntax highlighting, LSP diagnostics, statusline, and buffer tabs via `aether.nvim` and LazyVim hot-reloading.
- **System Telemetry (btop):** Spacecraft telemetry dashboard with dedicated gradients for CPU, Memory, Disk, and Network monitoring.
- **Shell Prompt (Zsh & Starship):** Ice cyan active symbols and muted directory pathing.
- **Browsers & Icons:** Chromium / Chrome theme color policy (`#080B14`) and `Yaru-blue-dark` icon theme.

---

## 🚀 Installation & Activation

### 1. Linking into Omarchy

To make AEGIS accessible to the Omarchy theme manager, create a symlink in your user themes directory:

```bash
mkdir -p ~/.config/omarchy/themes
ln -s /home/coder/themes/AEGIS ~/.config/omarchy/themes/aegis
```

### 2. Activating AEGIS

Switch to AEGIS instantly using the Omarchy CLI:

```bash
omarchy theme set aegis
```

Alternatively, open the graphical theme switcher:

```bash
omarchy theme switcher
```
And select **Aegis** from the carousel.

### 3. Cycling Wallpapers

To cycle through the 16 wallpapers in order:

```bash
omarchy theme bg next
```

Or open the interactive background switcher:

```bash
omarchy background
```

---

## 🔄 Rollback & Removal

AEGIS is completely modular and non-destructive.

### To switch back to your previous theme:

```bash
omarchy theme set "Mr Robot"
# Or any other installed theme:
# omarchy theme set "Tokyo Night"
# omarchy theme set "Nord"
# omarchy theme set "Catppuccin"
```

### To completely remove AEGIS:

```bash
# 1. Switch away from AEGIS first
omarchy theme set "Catppuccin"

# 2. Remove the symlink
rm -f ~/.config/omarchy/themes/aegis
```

---

## 📦 Publishing to Git

To publish this theme to GitHub or GitLab:

```bash
cd /home/coder/themes/AEGIS
git init
git add .
git commit -m "feat: initial release of AEGIS — Deep Space Command Center theme v1.0.0"
git branch -M main
git remote add origin https://github.com/<your-username>/omarchy-aegis-theme.git
git push -u origin main
```

---

## 📄 License

- Theme configuration and original artwork: [MIT License](LICENSE)
- NASA photography and scientific assets: Public Domain (U.S. Government Work)
