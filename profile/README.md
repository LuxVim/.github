<p align="center">
  <img src="https://github.com/user-attachments/assets/546ee0e5-30fd-4e37-b219-e390be8b1c6e" alt="LuxVim Logo" style="width: 50%; height: auto;" />
</p>

**LuxVim** is a high-performance, self-contained Neovim distribution built for developers who demand powerful features, responsive editing, and a sleek interface — without the setup overhead. This workspace contains both the complete LuxVim distribution and the standalone lux.nvim colorscheme plugin.

## 🚀 Quick Start

### Easy Installation

```bash
# Clone the LuxVim workspace
git clone https://github.com/LuxVim/lux-workspace.git

# Install LuxVim
cd lux-workspace/LuxVim && ./install.sh

# Launch LuxVim
lux
```

### What You Get

- **Custom Plugin Ecosystem**: Built-in terminal, dashboard, statusline, and utility plugins
- **30+ Beautiful Themes**: Including custom LuxVim themes and popular community favorites
- **Modern Tooling**: fzf integration, nvim-tree, lazy.nvim with lockfile support
- **Self-Contained**: No interference with existing Neovim configurations, uses `NVIM_APPNAME="LuxVim"` for complete separation
- **Instant Productivity**: Zero configuration required, works out of the box
- **Plugin Development System**: Hot-reload development with local debug plugins

## 👥 LuxVim Team

<table align="center">
  <tr>
    <td align="center" width="150">
      <a href="https://github.com/josstei">
        <img src="https://github.com/josstei.png" alt="josstei" width="80" height="80">
      </a>
      <br><br>
      <strong><a href="https://github.com/josstei">josstei</a></strong>
      <br>
      Creator & Core Developer
    </td>
    <td align="center" width="150">
      <a href="https://github.com/zejzejzej3">
        <img src="https://github.com/zejzejzej3.png" alt="zejzejzej3" width="80" height="80">
      </a>
      <br><br>
      <strong><a href="https://github.com/zejzejzej3">zejzejzej3</a></strong>
      <br>
      Web Development & Design
    </td>
  </tr>
</table>

## ✨ Key Features

### LuxVim Distribution Features

#### 🎛️ **Custom Plugin Ecosystem**
- **nvim-luxdash**: Beautiful startup dashboard with ASCII art and quick actions
- **nvim-luxterm**: Advanced terminal with floating windows and session management
- **nvim-luxmotion**: Smooth cursor and scroll animations with customizable easing
- **nvim-luxline**: Context-aware statusline with different modes for various windows
- **vim-easycomment**: Language-aware commenting system
- **vim-easyops**: Hierarchical command palette (Main → Git/Window/File/Code/Misc)
- **vim-backtrack**: File navigation history with intelligent split management

#### 🔧 **Development-Focused Tools**
- **Hot-Reload Plugin Development**: Place debug plugins in `debug/` directory
- **Cross-Platform Search**: Integrated grep/findstr with quickfix integration
- **FZF Integration**: Blazing fast file and text search
- **Git Integration**: Built-in git operations through easyops
- **Window Management**: Intelligent pane management with protected buffers

#### 🎨 **Visual Excellence**
- **Custom LuxVim Themes**: Sleak looking themes designed for LuxVim with both dark and light theme options
- **30+ Curated Themes**: From modern (Catppuccin, Tokyo Night) to classic (Gruvbox, Dracula)
- **True Color Support**: 24-bit RGB color rendering
- **Smooth Animations**: Configurable cursor and scroll animations
- **Custom Icons**: File type icons throughout the interface

## System Requirements

- **Neovim 0.8+** (recommended 0.9+)
- **Git** for plugin management
- **Unix-like system** (Linux, macOS, WSL)

## 🤝 Contributing

We welcome contributions to all LuxVim repositories:

1. **Fork** the repository
2. **Create** a feature branch
3. **Test** thoroughly with the existing ecosystem
4. **Submit** a pull request

## 📜 License

This project is open source and available under the **MIT License**.

## 🙏 Credits & Acknowledgments

### Core Infrastructure
- **[Neovim](https://neovim.io/)** - The extensible editor that makes this possible
- **[folke](https://github.com/folke)** - Creator of lazy.nvim
- **[Junegunn Choi](https://github.com/junegunn)** - Creator of fzf

### Community
- **Theme Authors**: 30+ theme maintainers who make LuxVim beautiful
- **Contributors**: Everyone who has contributed code, ideas, and feedback

---

<p align="center">
  <strong>✨ Step into a brighter development experience with LuxVim! ✨</strong>
</p>

<p align="center">
  <a href="https://luxvim.org">Website</a> •
  <a href="#installation--usage">Quick Start</a> •
  <a href="#development--customization">Customize</a> •
  <a href="#contributing">Contribute</a>
</p>
