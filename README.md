<div align="center">
<h1>Lilo Theme for Visual Studio Code</h1>

[![Version](https://img.shields.io/github/package-json/v/enBonnet/lilo-theme-vscode?color=3ECF8E&style=for-the-badge&label=VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=enbonnet.lilo-theme)
[![Open VSX Version](https://img.shields.io/static/v1?label=Open%20VSX&message=Download&color=9B8AE0&style=for-the-badge&logo=open-vsx)](https://open-vsx.org/extension/enBonnet/lilo-theme)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/enbonnet.lilo-theme?color=33B074&style=for-the-badge&label=Downloads)](https://marketplace.visualstudio.com/items?itemName=enbonnet.lilo-theme)

<img src="./images/icon.png" alt="Lilo Theme for Visual Studio Code" width="200">
</div>

## 📋 Table of Contents

- [✨ Features](#-features)
- [🎨 Preview](#-preview)
- [🚀 Installation](#-installation)
- [🎛️ Using the Theme](#-using-the-theme)
- [🎨 Color Palette](#-color-palette)
- [🛠️ Development](#-development)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [💖 Credits](#-credits)

## ✨ Features

- 🎨 Beautiful dark theme inspired by Lilo's brand colors
- 👀 Optimized for long coding sessions
- 🖥️ Supports all major programming languages
- 🎯 Perfect for Lilo developers
- 🌙 Two variants: Standard and Soft

## Description

This is the non-official Lilo Theme for Visual Studio Code, inspired by the [Lilo](https://lilohq.com/) brand colors.

## 🎨 Preview

### Base Theme
<div align="center">
<img src="./images/screenshots/base.png" alt="Lilo Theme Base" width="600">
</div>

### Soft Variant
<div align="center">
<img src="./images/screenshots/soft.png" alt="Lilo Theme Soft" width="600">
</div>

## 🎨 Color Palette

This theme uses a teal/cyan primary palette and neutral gray secondary palette derived from the Lilo brand:

| Role | Color | Hex | Preview |
|------|-------|-----|---------|
| Background | Near Black | `#161618` | ![#161618](https://via.placeholder.com/20/161618/161618) |
| Foreground | Off White | `#eff0f2` | ![#eff0f2](https://via.placeholder.com/20/eff0f2/eff0f2) |
| Selection | Teal Selection | `#009a9c3d` | ![#009a9c](https://via.placeholder.com/20/009a9c/009a9c) |
| Comments | Muted Gray | `#676a6a` | ![#676a6a](https://via.placeholder.com/20/676a6a/676a6a) |
| Cyan | Cyan Highlight | `#3de5e8` | ![#3de5e8](https://via.placeholder.com/20/3de5e8/3de5e8) |
| Green | Deep Teal | `#007670` | ![#007670](https://via.placeholder.com/20/007670/007670) |
| Orange | Warm Gold | `#E89B4C` | ![#E89B4C](https://via.placeholder.com/20/E89B4C/E89B4C) |
| Pink | Magenta | `#D06B9F` | ![#D06B9F](https://via.placeholder.com/20/D06B9F/D06B9F) |
| Purple | Soft Violet | `#9B8AE0` | ![#9B8AE0](https://via.placeholder.com/20/9B8AE0/9B8AE0) |
| Red | Error Red | `#E85757` | ![#E85757](https://via.placeholder.com/20/E85757/E85757) |
| Yellow | Mint Tint | `#b2f5f3` | ![#b2f5f3](https://via.placeholder.com/20/b2f5f3/b2f5f3) |

### UI Variants

| Variable | Hex | Purpose |
|----------|-----|---------|
| BGDarker | `#0c0c0d` | Darkest |
| BGDark | `#161618` | Near Black |
| BG | `#161618` | Main editor background |
| BGLight | `#363838` | Light panels |
| BGLighter | `#545656` | Hover states |

### ANSI Terminal Colors

| ANSI | Name | Hex | Bright Hex |
|------|------|-----|------------|
| 0/8 | Black | `#161618` | `#676a6a` |
| 1/9 | Red | `#E85757` | `#F07070` |
| 2/10 | Green | `#00afb4` | `#00c5ce` |
| 3/11 | Yellow | `#E8C857` | `#F0D870` |
| 4/12 | Blue | `#9B8AE0` | `#B0A0F0` |
| 5/13 | Magenta | `#D06B9F` | `#E080B0` |
| 6/14 | Cyan | `#3de5e8` | `#7beeee` |
| 7/15 | White | `#eff0f2` | `#f1f3f5` |

## 🚀 Installation

### VS Code Marketplace
[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/enbonnet.lilo-theme?style=for-the-badge&label=VS%20Code%20Marketplace&color=3ECF8E)](https://marketplace.visualstudio.com/items?itemName=enbonnet.lilo-theme)

### Open VSX Registry
[![Open VSX Registry](https://img.shields.io/open-vsx/v/enBonnet/lilo-theme?style=for-the-badge&label=Open%20VSX%20Registry&color=9B8AE0)](https://open-vsx.org/extension/enBonnet/lilo-theme)

## 🎨 Using the Theme

1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Preferences: Color Theme" and press Enter
3. Search for "Lilo Theme"
4. Select either "Lilo Theme" or "Lilo Theme (Soft)" from the list

### Recommended Settings

For the best experience, add these to your `settings.json`:

```json
{
  "workbench.colorTheme": "Lilo Theme",
  "editor.fontFamily": "'Victor Mono', Monaco, Menlo, 'Courier New', monospace",
  "editor.fontSize": 16,
  "editor.lineHeight": 1.5,
  "editor.fontWeight": "600",
  "editor.wordWrap": "on",
}
```

- [Victor Mono](https://rubjo.github.io/victor-mono/)


## 🎨 Theme Variants

- **Lilo Theme** - Vibrant, high-contrast version with the full Lilo color experience
- **Lilo Theme (Soft)** - Muted, desaturated version for reduced eye strain during long coding sessions

## 🛠 Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [pnpm](https://pnpm.io/) or npm

### Setup

```bash
# Install dependencies
pnpm install

# Build the theme
pnpm run build

# Package the extension
pnpm run package
```

### Project Structure

```
├── src/
│   └── lilo.yml      # Theme source file (YAML)
├── theme/
│   ├── lilo.json     # Generated theme
│   └── lilo-soft.json
├── scripts/
│   ├── build.js          # Build script
│   └── generate.js       # Theme generator
└── images/
    └── icon.png          # Extension icon
```

## 🤝 Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to:

1. Open an [issue](https://github.com/enbonnet/lilo-theme-vscode/issues)
2. Submit a pull request
3. Share your feedback

## 📬 Stay Updated

For updates, star this repository and follow me on [GitHub](https://github.com/enbonnet).

## 💖 Credits

- Inspired by the beautiful Lilo brand colors and design
- Special thanks to the VS Code community for their amazing theming support
- This theme is based on the [Dracula Theme](https://draculatheme.com/) schema, with colors adapted from the Lilo brand palette featuring tropical/beach aesthetics.
- Thanks to all contributors who help improve this theme

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Made with 🖤 by <a href="https://enbonnet.com">Ender Bonnet</a>
</div>
